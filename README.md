# Clinic Appointment Booking System

## intro

This project is a **Clinic Appointment Booking System** . It shows a real-world use case where patients can book appointments with doctors in various departments of a clinic. The database handles doctors, patients, appointments, departments, and payments, ensuring efficient tracking and management of clinic operations.

---

## ERD

- structure of the ERD:
  - Patients
  - Doctors
  - Appointments
  - Departments
  - Payments
- clinic appointment booking system relationships:
  - One-to-Many ( One department has many doctors)
  - Many-to-One (Many appointments belong to one patient)


---

## tools used

- MySQL
- for ERD i used dbdiagram.io

## How to Set Up the SQL File

1. **Open MySQL Workbench** 
2. Create a new schema,
   CREATE DATABASE clinic_db;
   then select database,
   USE clinic_db;
   then open and run the **clinic_booking_system.sql** file
