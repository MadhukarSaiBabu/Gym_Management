# Gym_Management

This project presents a **Gym Management System** implemented in C++ to streamline the handling of student gym membership records. The system supports essential file-based operations such as **creating**, **displaying**, **searching**, **appending**, and **deleting** gym member records, with data stored and managed using C-style file handling (`fopen`, `fread`, `fwrite`, `fclose`). Each student’s record includes their name, roll number, date of birth (DOB), and preferred gym time slot. The system uses a structured approach with the help of a `student` struct and a `Gym` class to encapsulate the functionalities.

The `create` method initializes new gym records, while the `display` method provides a tabular view of all existing records. The `search` function allows users to locate a member based on their roll number, and the `append` function supports adding new member records without overwriting existing data. The `del` method securely deletes a specific record by roll number using a temporary file as an intermediary for safe data transfer.

This project enhances understanding of **file handling**, **structured programming**, and **menu-driven interfaces** in C++. It is particularly useful for students learning about record management systems and file I/O in C++, providing a practical demonstration of applying programming concepts in real-life administration scenarios.



