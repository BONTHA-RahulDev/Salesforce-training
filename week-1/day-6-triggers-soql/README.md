# Day 6 - SOQL and Apex Triggers

# What is SOQL?

SOQL (Salesforce Object Query Language) is used to retrieve records from Salesforce objects. It is similar to SQL but designed specifically for Salesforce data.
---

# What is an Apex Trigger?

An Apex Trigger is code that runs automatically before or after events such as insert, update, delete, or undelete on Salesforce records.

---

# Flow vs Trigger

# Flow
- No-code automation
- Easy to build
- Best for simple business logic

# Apex Trigger
- Code-based automation
- Handles complex logic
- Better for advanced processing and integrations

---

# Before Trigger vs After Trigger

# Before Trigger
- Runs before saving records
- Used for validation or updating field values

# After Trigger
- Runs after records are saved
- Used for related records and notifications

---

# Trigger Use Cases

# 1. Student Registration
- Trigger Event: After Insert
- Action: Send welcome email

# 2. Low Attendance Alert
- Trigger Event: After Update
- Action: Send warning notification

# 3. Course Capacity Full
- Trigger Event: After Update
- Action: Notify faculty

# 4. Fee Payment Completion
- Trigger Event: After Update
- Action: Generate receipt

# 5. Exam Result Published
- Trigger Event: After Insert
- Action: Notify students

---

# Query Examples

- Find all students in Course A
- Find all courses handled by Faculty X
- Find students with attendance below 75%
- Find students who paid full fees
- Find courses with maximum enrollments

---

# Reflection

Enterprise systems need event-driven behavior because actions should happen automatically when data changes. This improves efficiency, reduces manual work, and provides faster responses to users.

Triggers and automation help businesses save time and maintain accuracy.
# SCREENSHOTS:
<img width="930" height="311" alt="Screenshot 2026-05-14 220041" src="https://github.com/user-attachments/assets/ce0aa8df-1ffd-4337-b693-8fc861afd2f5" />
<img width="931" height="307" alt="Screenshot 2026-05-14 220056" src="https://github.com/user-attachments/assets/fb339ac5-7f37-47ec-b7b1-85ed4f9e9ec6" />
