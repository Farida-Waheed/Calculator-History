# 🧮 MIPS Assembly Calculator with Linked List History

A powerful floating-point calculator implemented in **MIPS Assembly**, enhanced with a **linked list data structure** to track and manage the calculation history. The program offers a menu-based system allowing users to perform arithmetic operations, store results, reuse previous values, and delete specific entries.

---

## 🏫 Project Information

* **University:** Benha University, Faculty of Engineering (Shoubra)  
* **Department:** Communications and Computer Engineering  
* **Course:** Computer Organization  

---

## 👩‍💻 Team Members

* Abdelrahman Salah El-dein Abdelaziz  
* Farida Waheed Abdelbary  
* Mohamed Ahmed Mohamed Hassan  
* Raneem Ahmed Refaat 
* Razan Ahmed Fawzy   

---

## 📌 Project Overview

This MIPS program provides:

- Floating-point arithmetic (Add, Subtract, Multiply, Divide)
- Linked list storage of calculation results
- Menu-driven interaction with user prompts
- Reuse of the most recent result
- Deletion of individual history entries
- Viewing all stored results

---

## 🧠 System Features

- **Platform:** MIPS Assembly Language  
- **Data Structure:** Linked List (Dynamic Memory Allocation)
- **Operations:** Addition, Subtraction, Multiplication, Division
- **History Functions:** Insert, Print, Delete, Use Previous
- **User Interface:** Console menu with numeric options

---

## ⚙️ Menu Options

| Option | Function                     |
|--------|------------------------------|
| 1      | Perform Addition             |
| 2      | Perform Subtraction          |
| 3      | Perform Multiplication       |
| 4      | Perform Division             |
| 5      | View Calculation History     |
| 6      | Delete a Specific Result     |
| 7      | Use Previous Result          |
| 8      | Display Most Recent Result   |
| 9      | Exit Program                 |

---

## 🧾 How It Works

1. Program initializes and displays the main menu.
2. Based on input:
   - Prompts for one or two floating-point numbers.
   - Performs the operation using MIPS floating-point instructions.
   - Stores the result in a dynamically allocated linked list.
   - Offers the ability to delete or reuse results.
3. Returns to menu unless user chooses exit.

---

## 📐 Algorithm Flow

1. Print menu  
2. Take user selection  
3. Branch to appropriate operation:  
   - `Addition`, `Subtraction`, `Multiplication`, `Division`  
   - `Insert_float`, `Print`, `Delete_float`, `Use_previous_result`, `PrintItem`  
4. Display results or error messages  
5. Loop until Exit

---

## 🧪 Testing Results

| Scenario                      | Input       | Output / Action                      | Passed |
|-------------------------------|-------------|--------------------------------------|--------|
| Add 2 and 2                   | 2, 2        | 4.0 saved to history                 | ✅     |
| Subtract 3 from 5             | 5, 3        | 2.0 saved to history                 | ✅     |
| Multiply 3 and 2              | 3, 2        | 6.0 saved to history                 | ✅     |
| Divide 10 by 5                | 10, 5       | 2.0 saved to history                 | ✅     |
| View History                  | —           | Lists 4.0, 2.0, 6.0, 2.0             | ✅     |
| Delete Existing (2.0)         | 2.0         | Number removed from list             | ✅     |
| Delete Non-Existing (7.0)     | 7.0         | Error message: Not found             | ✅     |
| Use Previous Result           | —           | Stored in `$f1` for next operation   | ✅     |

---

## 💾 Project Files

* `Calculator_History.asm` – Full MIPS source code
* `CO_Project.pdf` – Detailed project documentation
* `CO_Project.pptx` – Summary presentation slides

---

## 🖼 Code Screenshots (Optional)

* First when we run the program

  ![image](https://github.com/user-attachments/assets/6310cbea-af24-4584-8e96-761738e3cb5f)
* For 'Exit'

  ![image](https://github.com/user-attachments/assets/337824b1-60ee-4f5f-9d8c-731fa73bd0d1)
* For 'Use previous result'

  ![image](https://github.com/user-attachments/assets/d60f0786-f4ae-49ac-9d48-6256944f3256)
  ![image](https://github.com/user-attachments/assets/ff23bc78-954b-48ac-bdd1-18dd6d48cfd1)
* For 'Addition'  

  ![image](https://github.com/user-attachments/assets/c54bd357-f058-4a97-8881-ba265ba192ad)
* For 'Subtraction'  

  ![image](https://github.com/user-attachments/assets/07c621dc-d0ca-453f-84ce-762944383092)
* For 'Multiplication'
  ![image](https://github.com/user-attachments/assets/07cebaf9-bc5e-46b2-829e-24e61d41ec1f)
* For 'Division'

  ![image](https://github.com/user-attachments/assets/1d6345c0-22df-47c3-b693-17ade4a0f007)
* For 'View history'

  ![image](https://github.com/user-attachments/assets/554cbbaa-cdda-4d30-8b55-cbcfe62e20ec)
* For 'Previous results'

  ![image](https://github.com/user-attachments/assets/a9bf7218-9a01-4903-ae0f-0deef5901c77)
* For 'Delete no.’ in case  “existing num” 
  
  ![image](https://github.com/user-attachments/assets/f9b20187-7ce9-4b16-9528-ffc7326c7743)
* Then choose'View history'

  ![image](https://github.com/user-attachments/assets/cda90ad9-7414-4dfb-ba46-e344dcf6b540)
* For 'Delete no.’ in case “not existing num”

  ![image](https://github.com/user-attachments/assets/8e944509-f21f-4f96-a26e-36328dc61b69)

---

## 🛠 Tools Used

* **MARS / QtSPIM** – MIPS Assembly simulator
* **Microsoft Word / PowerPoint** – Documentation & slides

---

## 🧑‍🏫 Learning Outcomes

- Implementing and managing a linked list in MIPS
- Handling floating-point I/O operations
- Structuring user interaction via menu-driven programs
- Using system calls (`syscall`) for float input/output
- Applying recursion-like looping without high-level language constructs

