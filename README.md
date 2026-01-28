# Hospital Management System

A **full-featured Hospital Management System** developed in **Java using Swing GUI**, implementing **Design Patterns** for scalable, secure, and maintainable software architecture. This project was developed as part of the **Design Patterns – Selected Lab of Software Engineering** course.

## 🏥 Key Pages & Features
- **Registration & Login**: Create accounts for Admins, Doctors, and Receptionists  
- **Add Doctor / Add Patient Pages**: Manage user data using **Builder pattern**  
- **View Doctors / Patients / Records Pages**: Table-based views with **role-based permissions**  
- **Book Page**: Manage patient appointments  
- **Add Record Page**: Issue medical records using **Prototype templates**  
- **Home Dashboard**: Dynamic UI that adjusts features based on user roles  
- **Emergency Cases**: Quickly register and track urgent cases  
- **Pharmacy Management**: Track medications and inventory  
- **Billing & Invoicing**: Handle patient payments  
- **Reports & Analytics**: Generate statistics on patients, appointments, and emergencies  
- **Department Management**: Organize doctors and staff by department  
- **Notifications & Alerts**: Keep users updated on appointments and emergencies  

## 🎯 Design Patterns Implemented
- **Singleton (DatabaseConnection)** – Single shared DB connection  
- **Factory Method (UserFactory)** – Create users dynamically based on role  
- **Builder (DoctorBuilder & PatientBuilder)** – Construct flexible user objects step-by-step  
- **Proxy (AccessControlProxy)** – Enforce access control for data operations  
- **Adapter (DatabaseAdapter)** – Simplify database interactions  
- **Prototype (MedicalRecordPrototype & Appointment)** – Clone standard records and appointments  

## 🛠 Setup Instructions
1. Install **SQL Server** and create a database named `HospitalDataBase`  
2. Update the connection string in `DatabaseConnection.java` with your server credentials  
3. Add the `mssql-jdbc` driver to the project libraries  
4. Open the project in your IDE and run `HospitalSystem.java`  

## 👥 Authors
- Abdelwahab Selim  
- Abdallah Mohamed  
- Fatma Emad  
- Aya Eltaher   

## 📂 Repository Structure
##  @Shenouda Safwat 
