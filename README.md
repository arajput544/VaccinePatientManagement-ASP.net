# 💉 Vaccine and Patient Management System

A Full-Stack ASP.NET Core MVC Web Application for Efficient Hospital Vaccine and Patient Management.

---

## 📝 Introduction

This is a web-based application developed to help hospital staff manage vaccines and patients. It allows tracking vaccine stock, administering doses, and maintaining a digital record of patient vaccination statuses.

---

## 🚀 Features

### 🏠 Home Page
- Navigation to:
  - **Vaccine Management**
  - **Patient Management**
![Dashboard](/Vaccine%20and%20Patient%20Management%20System_files/FrontPage.png)
---

### 💉 Vaccine Management

- **List Vaccines**: View all vaccines with details like name, doses required, doses received/left, etc.
![Dashboard](/Vaccine%20and%20Patient%20Management%20System_files/Vaccine.png)
- **Add New Vaccine**: Add a new vaccine type with relevant dosage info.
![Dashboard](/Vaccine%20and%20Patient%20Management%20System_files/AddVaccine.png)
- **Add New Doses**: Update vaccine stock when new doses arrive.
![Dashboard](/Vaccine%20and%20Patient%20Management%20System_files/NewDoses.png)
- **Edit Vaccine**: Update vaccine details.
![Dashboard](/Vaccine%20and%20Patient%20Management%20System_files/EditVaccine.png)

---

### 🧑‍⚕️ Patient Management

- **List Patients**: View patient info with vaccine details and dose dates.
![Dashboard](/Vaccine%20and%20Patient%20Management%20System_files/Patient.png)
- **Add New Patient**: Register a new patient and assign a vaccine.
![Dashboard](/Vaccine%20and%20Patient%20Management%20System_files/New%20Patient.png)
- **Receive 2nd Dose**: Mark a patient as having received the second dose and update stock accordingly.
![Dashboard](/Vaccine%20and%20Patient%20Management%20System_files/Patient.png)

---

## 🛠️ Technology Stack

- **ASP.NET Core MVC** – for scalable, maintainable web app structure
- **C#** – primary backend language
- **Entity Framework Core (EF Core)** – ORM for database operations
- **MS SQL Server** – database system
- **LINQ** – to query data in a type-safe way

---

## 🗄️ Database Access with EF Core

- Uses `AppDbContext.cs` to manage DB connection and define relationships.
- Two main models: `Patient` and `Vaccine`.
- Supports full CRUD operations via `DbSet<Patient>` and `DbSet<Vaccine>`.

---

## 💻 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/vaccine-patient-management.git
