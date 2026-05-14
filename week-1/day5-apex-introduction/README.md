# Day 5 – Apex Introduction

# What is Apex?

Salesforce Apex is a programming language used to implement custom business logic and automation inside the Salesforce platform. It is similar to Java and is mainly used when declarative tools like Flows are not sufficient.

Apex helps developers:
- Perform complex calculations
- Build integrations with external systems
- Create advanced validations
- Process large amounts of data
- Implement custom automation

---

# Difference Between Flow and Apex

| Flow | Apex |
|---|---|
| No-code / low-code tool | Programming language |
| Easy for simple automation | Best for complex logic |
| Faster to build | More flexible |
| Used by admins | Used by developers |
| Limited customization | Advanced customization possible |

---

# Difference Between Configuration and Coding

| Configuration | Coding |
|---|---|
| Built using clicks and settings | Built using programming |
| Easier and faster | More powerful and flexible |
| Limited functionality | Unlimited customization |
| Requires less technical knowledge | Requires programming knowledge |

---

# Real Examples Where Apex Is Needed

## 1. Complex Fee Calculation
In a college management system, fee calculation may depend on:
- Scholarships
- Hostel fees
- Sports quota discounts
- Late payment penalties

Such complex calculations are difficult using Flow alone, so Apex is needed.

---

## 2. External Payment Gateway Integration
If the system connects with online payment services or bank APIs, Apex is required to handle API requests and responses securely.

---

# 3. Advanced Eligibility Verification
A student may be eligible for registration only if:
- Attendance is above 75%
- Fees are fully paid
- No disciplinary issues exist
- Prerequisite subjects are completed

This requires advanced business logic, making Apex the better solution.

---

# Integrated College Management System Design

# CRM Usage
The College Management System uses Salesforce CRM to manage:
- Student admissions
- Courses
- Faculty details
- Attendance records
- Fee management

---

# Objects
Custom objects used:
- Student
- Course
- Faculty
- Attendance
- Fees

---

# Relationships
Relationships connect objects together:
- Student ↔ Course
- Faculty ↔ Course
- Student ↔ Fees

These relationships help maintain connected and organized data.

---

# Validation Rules
Validation rules ensure correct data entry.

Examples:
- Email field cannot be empty
- Attendance cannot exceed 100%
- Fees cannot be negative

---

# Flow Automation
Flows are used for:
- Admission confirmation emails
- Fee due reminders
- Attendance notifications
- Automatic status updates

---

# Apex Usage
Apex is used for:
- Eligibility verification
- Complex fee calculations
- Payment gateway integration
- Seat allocation logic

---

# Pseudocode Examples

# Example 1
IF seats are full  
THEN block registration

## Example 2
IF attendance < 75%  
THEN notify student

# Example 3
IF fees are unpaid  
THEN prevent hall ticket generation

# Example 4
IF payment successful  
THEN update fee status

---

# Reflection

# Why can’t all enterprise logic be built using only clicks and configuration?

Enterprise systems often contain complex business requirements such as advanced calculations, integrations with external systems, dynamic validations, and large-scale data processing. Declarative tools like Flow are useful for simple automation but have limitations when handling advanced scenarios.

Programming with Apex provides:
- Better flexibility
- Scalability
- Advanced customization
- Efficient handling of complex business logic

Therefore, enterprise applications eventually require programming to meet business needs effectively.

---

# Reflective Questions

# 1. Why is Apex needed if Salesforce already has Flows?
Flows are suitable for simple automation, while Apex is required for advanced logic, integrations, and complex processing.

# 2. When should developers prefer no-code solutions?
Developers should prefer no-code solutions for simple tasks like approvals, notifications, and basic automation because they are easier to maintain.

# 3. What problems require custom programming?
Problems involving integrations, advanced calculations, dynamic logic, and large data processing require custom programming.

# 4. Why is business logic important in enterprise systems?
Business logic ensures that enterprise applications follow organizational rules, maintain accuracy, and automate important processes.

# 5. Why should developers avoid unnecessary coding?
Unnecessary coding increases maintenance complexity, debugging difficulty, and development time.

# 6. How does programming increase flexibility?
Programming allows developers to create highly customized solutions based on specific business requirements.

# ScreenShots:
<img width="898" height="324" alt="Screenshot 2026-05-14 125232" src="https://github.com/user-attachments/assets/962b12dd-25d6-4317-939e-48de0c251069" />
<img width="887" height="319" alt="Screenshot 2026-05-14 125254" src="https://github.com/user-attachments/assets/12a0b144-7dd4-4386-ae6e-24439e553683" />
