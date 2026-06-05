# 📝 Notes – Day 18

## What is Data Modeling?

Data Modeling is the process of designing how data is organized, stored, and related within Salesforce. It helps businesses manage information efficiently and maintain data integrity.

---

## Custom Objects

Custom Objects are user-created objects that store business-specific data.

Examples:

- Candidate
- Position
- Job Application

---

## Custom Fields

Custom Fields store additional information required by a business process.

Examples:

- Candidate Skills
- Expected Salary
- Application Status

---

## Object Relationships

Relationships connect records between different objects.

### Lookup Relationship

- Creates a loose connection between objects.
- Parent and child records can exist independently.

### Master-Detail Relationship

- Creates a strong connection between objects.
- Child records depend on the parent record.
- Supports roll-up summary fields.

---

## What are Record-Triggered Flows?

Record-Triggered Flows are automations that run automatically when a record is created, updated, or deleted.

They help automate business processes without writing code.

---

## Flow Builder Components

### Start Element

Defines when the flow begins.

### Decision Element

Adds logic and conditions to the flow.

### Update Records

Updates record information automatically.

### Create Records

Creates new records during automation.

### Actions

Performs tasks such as sending emails or notifications.

---

## Benefits of Record-Triggered Flows

- Automates repetitive tasks
- Reduces manual effort
- Improves business efficiency
- Ensures data consistency
- Provides no-code automation

---

## Recruiting App Data Model

Objects Used:

- Position
- Candidate
- Job Application

Relationships:

- A Candidate can apply for multiple Positions.
- A Position can receive multiple Applications.
- Job Application links Candidates and Positions.

---

## Key Benefits

- Organized data structure
- Efficient record management
- Automated business processes
- Improved user productivity
- Scalable application design
