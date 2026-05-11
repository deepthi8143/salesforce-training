# 📘 Salesforce Day 3 Notes

# 🌐 Salesforce Data Modeling

Salesforce stores business information using:
- Objects
- Fields
- Records
- Relationships

These components help businesses organize and manage enterprise data efficiently.

---

# 📦 What are Objects?

Objects are database tables used to store information in Salesforce.

Each object contains:
- Fields
- Records
- Relationships

### Examples
- Student
- Faculty
- Course
- Department

Objects help organize business data properly.

---

# 📝 What are Fields?

Fields store specific information inside records.

### Examples
- Student Name
- Email
- Phone Number
- Course Name

Fields define the type of data stored inside the system.

---

# 📄 What are Records?

Records are individual entries inside objects.

### Example

| Student Name | Email | Phone |
|---|---|---|
| Rahul | rahul@gmail.com | 9876543210 |

This single row is called a Record.

---

# 🔹 Standard vs Custom Objects

## Standard Objects
Objects already available in Salesforce.

### Examples
- Account
- Contact
- Lead
- Opportunity

---

## Custom Objects
Objects created according to business requirements.

### Examples
- Student Object
- Faculty Object
- Department Object

Custom Objects help businesses build specialized systems.

---

# 🔗 Salesforce Relationships

Relationships connect objects together and maintain structured enterprise data.

---

## Lookup Relationship

Lookup Relationships connect one object with another object.

### Examples
- Student → Course
- Faculty → Department
- Course → Department

### Benefits
- Organized data management
- Better reporting
- Easy navigation between records

---

# 🏫 College Management System Design

## Objects Created
- Student
- Faculty
- Course
- Department

---

## Relationships

| Parent Object | Child Object | Relationship |
|---|---|---|
| Course | Student | Lookup |
| Department | Faculty | Lookup |
| Department | Course | Lookup |

---

# 🧮 Formula Fields

Formula Fields automatically calculate values based on formulas.

---

## Formula Field Examples

### Full Name
Combines:
- First Name
- Last Name

### Remaining Seats
Calculates:
Maximum Seats - Filled Seats

### Percentage
Calculates student percentage automatically.

---

## Benefits of Formula Fields
- Saves time
- Reduces manual work
- Improves accuracy
- Provides real-time calculations

---

# ✅ Validation Rules

Validation Rules prevent invalid data from being saved.

---

## Validation Rule Examples

### Email Cannot Be Empty
Prevents saving records without email.

### Student Age Cannot Be Negative
Blocks invalid age values.

### Course Seats Cannot Exceed Limit
Restricts invalid seat entries.

---

## Benefits of Validation Rules
- Improves data quality
- Prevents incorrect entries
- Maintains consistency
- Reduces business errors

---

# 🏢 Importance of Structured Enterprise Data

Structured data is important because companies manage huge amounts of information daily.

Structured systems help:
- Maintain relationships
- Improve reporting
- Reduce duplicate data
- Increase scalability

Random spreadsheets become difficult to manage when business data grows large.
