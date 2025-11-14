# Bank-Management-System
A console-based Bank Management System built in C++ using AVL Trees for efficient account storage and Linked Lists for transaction logs. The system supports admin, staff, and ATM operations with secure PIN-based authentication.

__Features__  

->Account creation, deletion, search, and updates  
->Deposit and withdraw operations  
->Separate Admin, Staff, and ATM modules  
->Transaction logging using linked lists  
->Auto-generated account numbers  
->Fast O(log n) account lookups using AVL Trees  

__Data Structures__  
->AVL Tree → Stores account details; supports balanced insert/search/delete  
->Linked List → Maintains logs for each account  


__Files__  
->Avl.h            – AVL Tree implementation    
->Linked_List.h    – Log management using Linked Lists    
->Untitled1.cpp    – Main logic + interface  

__Command to Run__  
g++ Untitled1.cpp -o bank  
./bank  


__Summary__  
This project demonstrates the use of core data structures to build a functional banking system. By combining AVL Trees with Linked Lists, the system ensures fast data access, organized storage, and an interactive multi-role interface.
