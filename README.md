# Hospital Management System

A console-based Hospital Management System implemented in Java using JDBC and MySQL.

## Table of Contents

- Features
- Getting Started
  - Prerequisites
  - Setup
  - Run the Application
- Usage
- Database Schema
- Contributors
  
## Features

- **Add Patient:** Capture patient information and add them to the system.
- **View Patients:** Display a list of all registered patients.
- **View Doctors:** List all doctors and their specializations.
- **Book Appointment:** Reserve appointments with available doctors on specific dates.
- **View Appointments:** Retrieve a list of appointments for a given patient.
- **Cancel Appointments:** Remove booked appointments for patients.

## Getting Started

### Prerequisites

- Java Development Kit (JDK)
- MySQL Database
- MySQL Connector/J JDBC Driver

### Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/HospitalManagementSystem.git
    cd HospitalManagementSystem
    ```

2. Configure the MySQL database:

    - Create a database named `hospital`.
    - Update database connection details in `HospitalManagementSystem.java`.

### Run the Application

1. Compile and run the main program:

    ```bash
    javac HospitalManagementSystem.java
    java HospitalManagementSystem
    ```

2. Follow the on-screen menu to interact with the Hospital Management System.

## Usage

- **1. Add Patient:** Enter patient details to register new patients.
- **2. View Patients:** Display a list of all registered patients.
- **3. View Doctors:** List all doctors along with their specializations.
- **4. Book Appointment:** Schedule appointments with available doctors.
- **5. View Appointments:** Retrieve a list of booked appointments for a specific patient.
- **6. Cancel Appointments:** Cancel previously booked appointments.
- **7. Exit:** Terminate the Hospital Management System.

## Database Schema

Tables:

- **patients:** Stores patient information.
- **doctors:** Manages details about doctors.
- **appointments:** Records patient appointments.

## Contributors

- Madhan M.


