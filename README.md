# Hospital Facility Management System (HFMS) 🏥

A comprehensive desktop application designed to optimize the management of healthcare facilities and medical personnel. Built with a focus on **Unit-Based Management**, this system allows for organized tracking of doctors, staff, and facilities across various hospital departments.

## 🚀 Key Features
* **Unit-Centric Personnel Management:** Organize and view Doctors, Nurses, and Staff according to their assigned hospital units.
* **Facility Resource Tracking:** Real-time management and modification of hospital facilities and equipment.
* **Modular Navigation:** Multi-level dashboard for quick access to different administrative modules.
* **Database Integration:** Reliable data persistence using a centralized MySQL connection handler.
* **Dynamic Table Updates:** Interactive UI components that fetch and display real-time data from the `facility_management_hospital` database.

## 🛠️ Tech Stack
* **Language:** Java
* **Framework:** Java Swing (GUI)
* **IDE:** NetBeans
* **Database:** MySQL (JDBC)
* **Architecture:** Modular Desktop Application

## 📂 Project Structure & Logic
* **`db.java`**: Centralized database connection class using the JDBC driver.
* **`Homemain.java`**: The primary entry point providing top-level access to Facility and Staff categories.
* **`Home.java`**: A secondary navigation layer for filtering between Doctors, Nurses, and General Staff.
* **`Doctor.java` / `Facilities.java`**: Specialized modules for CRUD operations (Create, Read, Update, Delete) for specific hospital entities.

## 👥 Collaborative Contribution
This project was developed as a team effort. My specific contributions included:
* **Database Architecture:** Designing the relational schema for the `doctor` and `facility` tables.
* **Backend Integration:** Developing the `db.mycon()` connection logic to ensure secure data handling.
* **UI Development:** Implementing the `tbload()` methods and JTable integration for real-time data visualization.

## 🔧 Setup & Installation
1. **Prerequisites:** Install JDK 8+ and MySQL Server.
2. **Database Setup:** - Create a database named `facility_management_hospital`.
   - Ensure the user credentials match the parameters in `db.java` (default: `root` with no password).
3. **Execution:**
   - Clone the repository.
   - Open the project in NetBeans.
   - Run `Homemain.java` to start the application.

---
*Developed for the Health Information Technology (Health IT) Portfolio.*
