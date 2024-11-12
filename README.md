<h1>Hospital Database Analysis Using MySQL</h1>
Project Overview

This project involves creating and analyzing a comprehensive database for a hospital using SQL within MySQL Workbench. The database is designed to enable efficient data retrieval, allowing hospital management, doctors, and staff to access critical information on patients, departments, and appointments. This centralized data system enhances patient care, operational efficiency, and data-driven decision-making.

**Key Objectives**

The primary aim of this project was to answer crucial business and operational questions in a hospital setting, providing insights to improve healthcare management. These objectives include:

<h3>Database Entities:</h3>

1. Doctors: Stores details of doctors, their departments, patients they treat, and scheduled appointments.

2. Patients: Contains patient information, including demographics, diagnoses, medical history, and billing details.

3. Departments: Organizes doctors within specific hospital departments, showing departmental operations and staff assignments.

4. Cafeteria: Manages cafeteria details, including staff members and the type of food provided to patients.

5. Staff: Tracks all staff members, their roles, and department assignments, including non-medical personnel like cafeteria workers.

6. Medical Bills: Keeps records of billing information associated with each patient.

7. Laboratory Exams: Maintains records of medical tests and examinations for patients.

8. Patient Diagnoses: Stores diagnosis information for each patient.

9. Medication: Tracks medications prescribed to patients, along with dosage requirements.

10. Appointments: Schedules and organizes patient appointments with doctors.

<h3>Relationships between Entities:</h3>

The database establishes structured relationships among entities to streamline access to critical data:

1. Departments and Doctors: Each department has multiple doctors, and each doctor is assigned to one department.

2. Doctor-Patient Relationships: Doctors can treat multiple patients, and each patient may have multiple doctors.

3. Patient Billing: Patients receive multiple bills, each linked to one specific patient.

4. Staff Assignments: Staff members work in one cafeteria, and each cafeteria serves multiple staff members.

5. Doctor Appointments: Doctors have multiple appointments with patients, and each appointment is linked to one doctor.

<h3>Key SQL Queries:</h3>

Advanced SQL queries were employed to address specific business needs, including:

1. Diagnoses: Retrieve doctors who have treated patients with specific conditions, such as “Diabetes.”

2. Department Staff Count: Find the total number of workers in each department.

3. Patient Contact Information: List names and phone numbers of patients diagnosed with particular conditions.

4. Billing Information: Calculate the total salary expenditure for all staff.

5. Medication Details: List patients with specific prescribed medications.

6. Doctor Appointments: Retrieve doctors by department and order them by salary from highest to lowest.

<h3>Approach</h3>

I utilized SQL queries in MySQL Workbench to efficiently manage and analyze the hospital's data. The process involved:

1. Database Design: Structured the database to include all relevant entities and establish relationships.

2. Query Execution: Wrote SQL queries to answer operational questions related to patient care, staff management, and resource allocation.

3. Insight Generation: Interpreted the results to provide actionable insights for improving departmental efficiency, scheduling, and patient outcomes.

<h3>Conclusion</h3>

This project highlights the essential role of SQL in healthcare data management. By centralizing patient and staff data, the database supports accurate, timely medical decisions, enhances hospital operational efficiency, and improves patient outcomes. The insights gained can aid in staff scheduling, inventory management, and optimizing patient care strategies.

<h3>Tools Used</h3>

MySQL, MySQL Workbench
