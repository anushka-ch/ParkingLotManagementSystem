# Parking Lot Management System

A C-based Parking Lot Management System that handles:

- Vehicle entry and exit  
- Slot allocation  
- Time-based billing  
- Vehicle search  
- Real-time slot availability  
- Persistent log history with file handling  

---

## ✅ Features

- **User Login** – Secure entry (admin only)  
- **Dynamic Slot Management** – Automatically finds and assigns slots  
- **Charge Calculation** – ₹0.5 per minute (based on parking duration)  
- **File Handling** – Saves active parking data and log history  
- **Log Summary Report** – Displays current and past records  
- **Modular Design** – Uses structures, pointers, and functions  

---

## 🛠 Technologies Used

- **Language:** C  
- **Compiler:** GCC  
- **IDE:** VS Code  
- **Version Control:** Git + GitHub  
- **Key Concepts:**  
  - Pointers  
  - Structures  
  - File I/O  
  - Dynamic Memory Allocation  

---

## 🧪 How to Compile and Run

```bash
gcc main.c parking.c -o ParkingSystem.exe
./ParkingSystem.exe
📁 File Descriptions
File	Purpose
main.c	Entry point and menu system
parking.c	All core functionalities (login, park, exit)
parking.h	Structure definitions and function declarations
parking_data.txt	Stores active parked vehicle data
parking_log.txt	Stores full session history

👤 Author
Anushka
Student Project – 2025
## License

This project is *not licensed for reuse*.  
Please do not copy, publish, or distribute this code without permission.

