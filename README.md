# 🏥 Hospital Management System

## 📜 Description

This **Hospital Management System** is a C-based program designed to handle basic operations like admitting and discharging patients and doctors. It includes functionalities for managing records with detailed information about patients and doctors, stored in external files for persistent data handling.

---

## ✨ Features

- **Patient Management**:
  - Admit new patients and store details.
  - View a complete list of admitted patients.
  - Discharge patients and remove their records.

- **Doctor Management**:
  - Add new doctors and store their details.
  - View a complete list of registered doctors.
  - Discharge doctors and remove their records.

- **File-Based Data Persistence**:
  - Patient records are stored in `patient.txt`.
  - Doctor records are stored in `doctor.txt`.

- **Date Recording**:
  - Automatically records the current date for entries using `time.h`.

- **User-Friendly Console Menu**:
  - Interactive menu-driven interface for easy navigation.

---

## 📂 File Structure

- `patient.txt`: Stores patient records in binary format.
- `doctor.txt`: Stores doctor records in binary format.
- `temp.txt`: Temporary file for handling record deletion.

---

## 🛠️ How to Compile and Run

1. **Prerequisites**:
   - A C compiler (e.g., GCC).

2. **Compile the Code**:
   ```bash
   gcc hospital_management.c -o hospital_management
3. **Run the Program**:
```bash
./hospital_management
```
## 📋 Menu Options
- Admit Patient:

  - Input patient details including ID, name, address, and disease.
  - Automatically stores the current date of admission.
- Patient List:

  - Displays all admitted patients in a tabular format.
- Discharge Patient:

  - Remove a patient record using their unique ID.
- Add Doctor:

  - Input doctor details including ID, name, address, and specialization.
  - Automatically stores the current date of addition.
- Doctors List:

  - Displays all registered doctors in a tabular format.
- Discharge Doctor:

  - Remove a doctor record using their unique ID.
## 📄 License
This project is licensed under the MIT License.

## 👤 Author
[Debkumar Baksi](https://www.linkedin.com/in/debkumar-baksi-269738279/) 


## 🚀 Usage Example
- Launch the program and navigate through the menu:
  - Select 1 to admit a patient.
  - Select 2 to view the list of admitted patients.
  - Select 3 to discharge a patient, and so on.
- All updates are reflected in the corresponding data files (patient.txt, doctor.txt).
