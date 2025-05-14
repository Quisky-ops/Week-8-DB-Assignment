# Clinic Booking System

## Description

The **Clinic Booking System** is a MySQL-based database management system designed to help manage clinic operations such as patient records, doctor profiles, appointments, departments, and medical records. It features a well-structured relational database model using best practices including primary keys, foreign keys, constraints, and many-to-many relationships.

## Features

- Manage patient and doctor information
- Schedule and track appointments
- Organize departments and assign doctors
- Record diagnosis and treatment history
- Enforce data integrity through relationships and constraints

## How to Run / Setup the Project

### Requirements

- MySQL Server installed (v5.7 or higher recommended)
- MySQL Workbench or any compatible SQL editor

### Steps

1. **Download the SQL file:**
   - The project SQL file is named: `clinic_booking_system.sql`

2. **Open MySQL Workbench** (or your preferred SQL editor).

3. **Create a new schema/database:**
   ```sql
   CREATE DATABASE clinic_db;
   USE clinic_db;

4. Import the SQL file:

   In MySQL Workbench:

   File → Open → Select clinic_booking_system.sql
   Execute the script to create all tables and constraints
