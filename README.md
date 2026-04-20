
🏠 Vehicle Fleet Management System using Linked List in C



📌 Project Title
Vehicle Fleet Management System using Linked List and File Handling in C




👥 Team Members

Student 1: P.Kartheek

Student 2: N.Yaswanth




❓ Problem Statement
To design and implement a vehicle fleet management system that allows users to:

Add new vehicles

Delete vehicle records

Update vehicle details

Search for vehicles

Display all vehicle records

The system should also store data permanently using file handling so that records are not lost after program execution.




📊 Data Structure Used
🔹 Singly Linked List
Each node represents a vehicle

Stores:

Vehicle ID

Vehicle Name

Driver Name

Status (Available / In Use)

🔹 File Handling (Binary File)
Used to store vehicle data permanently in vehicles.dat





⚙️ Algorithm Explanation
1. Add Vehicle
Create a new node

Take input (Vehicle ID, Name, Driver, Status)

Insert at beginning of linked list

Save all records to file

2. Delete Vehicle
Search for vehicle by ID

Remove node from linked list

Update file

3. Update Vehicle
Search vehicle

Modify details (Name / Driver / Status)

Save updated list to file

4. Search Vehicle
Traverse linked list

Compare vehicle IDs

Display details if found

5. Display All Vehicles
Traverse entire linked list

Print all records

6. File Handling
Save: Write all nodes into binary file

Load: Read file and recreate linked list at program start




🧾 Compilation Instructions
Step 1: Compile the program
gcc fleet.c -o fleet
Step 2: Run the program
./fleet




📂 File Used
vehicles.dat → Stores vehicle data permanently
<img width="442" height="410" alt="Screenshot 2026-04-21 003056" src="https://github.com/user-attachments/assets/27c8e184-16dc-4a6b-9571-8c47bf22839e" />
<img width="508" height="399" alt="Screenshot 2026-04-21 003106" src="https://github.com/user-attachments/assets/1b7b7d4b-9cf8-4738-898e-9e5d9dd9e9ca" />
<img width="662" height="628" alt="Screenshot 2026-04-21 003134" src="https://github.com/user-attachments/assets/75d2b127-15cb-41b6-b0f5-bcc1d65e8bca" />
<img width="551" height="427" alt="Screenshot 2026-04-21 003147" src="https://github.com/user-attachments/assets/ba74e445-1149-4967-9705-9528bc371cc2" />
<img width="490" height="376" alt="Screenshot 2026-04-21 003156" src="https://github.com/user-attachments/assets/677b453a-c26e-4463-a77f-c13a0b445334" />
<img width="528" height="293" alt="Screenshot 2026-04-21 003216" src="https://github.com/user-attachments/assets/f8668595-9647-4df9-91b2-573ce99f2f8d" />
<img width="508" height="255" alt="Screenshot 2026-04-21 003226" src="https://github.com/user-attachments/assets/823c5f00-f8fa-452d-88b2-3cf2457f45d3" />

🚀 Features
Linked List implementation

File persistence

CRUD operations

Simple menu-driven interface

📌 Sample Menu
1. Add Vehicle
2. Delete Vehicle
3. Update Vehicle
4. Search Vehicle
5. Display All Vehicles
6. Exit




🧾 Conclusion
This project demonstrates how data structures like linked lists combined with file handling can be used to build a simple and efficient vehicle fleet management system in C.

