Project Overview
This project involves designing and implementing a relational database for DentistX, a hypothetical dental clinic located in Gotham City. The goal is to transition the clinic from using Excel sheets for scheduling and patient management to a structured relational database system. The design includes entities for dentists, patients, appointments, and rooms, with appropriate relationships and data normalization.

Key Tasks
1. Database Design
Entities and Attributes:

Identify the required entities (relations) for the database.
For each entity, list all relevant attributes that should be stored.
Keys:

Identify candidate keys, primary keys, and foreign keys for each entity.
Entity-Relationship Model (ERD):

Design a high-level ER model that defines relationships between the entities identified.
Database Creation:

Create an empty DentistX database and implement the database structure based on the ER model.
Make suitable assumptions for any missing requirements in the provided scenario.
2. Data Insertion
Insert at least 10 dummy records in each primary table and 20 records in each detailed/child table.
3. SQL Queries
Write SQL queries to retrieve specific data from the DentistX database:

(a) Which dentist treated the fewest number of patients?
(b) List the number of appointments per week in the order of date and time.
(c) Retrieve patient details for those whose treatments spanned more than one appointment.
(d) Retrieve the list of appointments where no student trainees were assigned.
(e) Retrieve the room with the least number of appointments.
(f) Retrieve the list of patients aged over 55.
(g) Calculate the total hours spent by each doctor on all appointments.
4. Database Design Justification
Provide a paragraph explaining why the designed database is in good normalized form.

5. Concurrency and Isolation in Relational Databases
Write a short explanation of your understanding of concurrency and isolation in relational databases.

6. NoSQL vs Relational Databases
Provide an argument about whether a NoSQL database could be a better fit for DentistX compared to a relational database. Give examples to support your argument.

Business Rules
One patient can be assigned to a maximum of one senior dentist and a trainee dentist.
For hygienic control, one hygienist and a maximum of two trainee dentists can be assigned.
For more complex treatments, a senior dentist and up to two or more trainees may be assigned.
Appointment slots follow a structured time frame, and rooms must be reserved for each appointment.
Scenario
Clinic Details: The clinic has 31 employees, including dentists, hygienists, receptionists, and other staff.
Appointments: Appointments are scheduled in 1.5-hour slots, and rooms are assigned for each slot.
Existing System: Currently, the clinic uses Excel sheets for patient and appointment management, leading to delays and inefficiencies.
Getting Started
Database Setup:

Clone this repository.
Run the SQL scripts to create the database and insert dummy data.
Running Queries:

Execute the provided SQL queries to retrieve data and test the functionality.
Assumptions
Dummy data for patients, appointments, dentists, and other entities can be added as needed.
Assumed that each patient has a unique ID and a dentist is assigned per appointment.
Technologies
Database: MySQL or any other SQL-based relational database system.
SQL: For creating, inserting, and querying the database.
