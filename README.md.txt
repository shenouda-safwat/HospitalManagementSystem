# Medical Clinic Management System

A full-featured Hospital Management System developed in **Java using Swing GUI** applying **Design Patterns** for scalable and maintainable architecture.

## 📌 Key Pages & Features
- **Registration & Login**: Create accounts for Admins, Doctors, and Receptionists  
- **Add Doctor / Add Patient**: Manage user data using Builder pattern  
- **View Doctors / Patients / Records**: Table views with role-based permissions  
- **Book Page**: Manage patient appointments  
- **Add Record Page**: Use Prototype templates to create records  
- **Home Dashboard**: Dynamic UI based on user role

## 🎯 Design Patterns Implemented
- **Singleton** – Single database connection session  
- **Factory Method** – Dynamic User creation  
- **Builder** – Construct flexible user objects  
- **Proxy** – Secure access control for operations  
- **Adapter** – Simplify database interactions  
- **Prototype** – Clone objects like records & appointments

## 🛠 Setup Instructions
1. Install SQL Server & create `HospitalDataBase`  
2. Update connection string in `DatabaseConnection.java`  
3. Add `mssql-jdbc` driver to library path  
4. Run the Java application from your IDE

---

## 🚀 3) رفع المشروع على GitHub
افتح **Git Bash / Terminal** داخل مجلد المشروع (`HospitalManagementSystem`) ثم:

```bash
git init
git add .
git commit -m "Initial commit – Hospital Management System"
git remote add origin https://github.com/shenouda-safwat/HospitalManagementSystem.git
git branch -M main
git push -u origin main
