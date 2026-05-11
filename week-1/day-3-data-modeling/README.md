# Day 3 – Salesforce Data Modeling

# 1. Difference Between

# App
An App in Salesforce is a collection of tools, tabs and objects used for a specific business purpose.

# Object
An Object is like a database table that stores information.

# Record
A Record is a single row of data inside an object.

# Field
A Field stores a specific piece of information inside a record.

---

# 2. Standard vs Custom Objects

Standard Objects are already provided by Salesforce such as Account, Contact and Opportunity.

Custom Objects are created by users based on business needs such as Student, Faculty and Course.

---

# 3. College Management System Data Model

# Objects
- Student
- Faculty
- Course
- Department

# Relationships
- One Department can have many Students
- One Department can have many Faculty members
- One Faculty can teach many Courses
- One Course can have many Students

# Relationship Types
- Student → Department (Lookup)
- Faculty → Department (Lookup)
- Course → Faculty (Lookup)
- Student → Course (Lookup)

# Diagram

<img width="900" height="1600" alt="WhatsApp Image 2026-05-11 at 4 33 03 PM" src="https://github.com/user-attachments/assets/9922c2e2-749e-4206-a180-5cac314799ae" />



# 4. Formula Fields

# Full Name
Combines First Name and Last Name automatically.

# Why automatic?
It reduces manual work and avoids typing mistakes.

# Percentage
Calculates percentage from total marks automatically.

# Why automatic?
It saves time and keeps calculations accurate.

# Remaining Seats
Calculates available seats after student registrations.

# Why automatic?
It helps colleges track seat availability instantly.

---

# 5. Validation Rules

# Email cannot be empty
Prevents saving student records without email.

Problem prevented:
Important communication will not be missed.

# Student age cannot be negative
Prevents invalid age values.

Problem prevented:
Incorrect student data will not enter the system.

# Course seats cannot exceed limit
Prevents adding students beyond seat capacity.

Problem prevented:
Avoids overbooking of courses.

---

# 6. Reflection

Companies need structured data because large amounts of business information must be organized properly. Structured data helps companies quickly find records, maintain relationships between data, generate reports and avoid mistakes. Random spreadsheets become difficult to manage when data grows large.



# 7. Reflective Questions

# 1. Why can’t companies manage everything using Excel sheets?
Excel sheets become difficult to manage when data becomes very large and complex.

# 2. Why are relationships important between objects?
Relationships connect related data and make systems organized.

# 3. What problems happen if data is inconsistent?
It creates confusion, wrong reports and business errors.

# 4. Why should repetitive calculations be automated?
Automation saves time and reduces human mistakes.

# 5. Why should invalid data be blocked early?
It keeps the database clean and accurate.

# 6. Why is Salesforce called a metadata-driven platform?
Because most customization is done without coding using metadata.
