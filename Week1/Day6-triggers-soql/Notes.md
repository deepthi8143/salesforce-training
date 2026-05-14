# 📘 Salesforce Day 6 Notes

# 🌐 Salesforce Database Concepts

Salesforce stores business information inside objects and records.

Data can be:
- Retrieved
- Updated
- Deleted
- Queried

using Salesforce database operations.

---

# 🔍 What is SOQL?

SOQL stands for Salesforce Object Query Language.

It is used to retrieve records from Salesforce objects.

---

## Example Queries

- Find all students in Course A
- Find students with attendance below 75%
- Find all courses handled by Faculty X

---

# 🔎 What is SOSL?

SOSL stands for Salesforce Object Search Language.

Used to search text across multiple objects.

---

# ⚙️ DML Operations

DML stands for Data Manipulation Language.

Used to:
- Insert records
- Update records
- Delete records

---

# ⚡ What is an Apex Trigger?

Apex Trigger is a piece of code that runs automatically when data changes happen in Salesforce.

Triggers help systems react automatically to events.

---

# 🔄 Trigger Events

Triggers execute during events such as:
- Before Insert
- After Insert
- Before Update
- After Update
- Before Delete
- After Delete

---

# 🟢 Before Trigger

Runs before data is saved.

### Used For
- Validation
- Updating values before saving

---

# 🔵 After Trigger

Runs after data is saved.

### Used For
- Sending notifications
- Updating related records
- External integrations

---

# 🔁 Flow vs Trigger

| Flow | Trigger |
|---|---|
| No-code automation | Code-based automation |
| Easy to maintain | Handles complex logic |
| Best for simple workflows | Best for advanced logic |

---

# 🏫 Trigger Use Cases (College Management System)

## 1. After Student Registration
### Action
Send welcome email automatically.

---

## 2. After Course Becomes Full
### Action
Notify faculty automatically.

---

## 3. After Attendance Drops Below 75%
### Action
Send warning notification.

---

## 4. After Fee Payment
### Action
Generate receipt automatically.

---

## 5. After Student Record Update
### Action
Update related department records.

---

# 🧠 Why Enterprise Systems Need Event-Driven Behavior

Enterprise systems handle large amounts of data and activities daily.

Systems must react automatically when events happen.

Examples:
- Notifications
- Updates
- Approvals
- Alerts

Event-driven systems improve:
- Speed
- Accuracy
- Productivity
- Automation efficiency
