# Leave Management System - Final Project Phase 2

## Project Overview

The Leave Management System is an enterprise Salesforce application used to manage employee leave requests, approval workflows, notifications, reporting, and analytics.

---

## Final Architecture

### Frontend Layer

Lightning Web Components (LWC)

Components:

- leaveApplicationForm
- leaveHistory
- leaveBalanceDashboard
- managerApprovalPanel
- leaveAnalyticsDashboard

### Backend Layer

Apex Classes:

-leaveController
-leaveService

## Database

Custom Objects:

-Employee
-Leave Request

## Automation

-Record Triggered Flows
-Email Notifications
-Approval Processes

---

## Approval Workflow

Employee applies for leave

↓

System validates details

↓

Leave request is saved

↓

Manager receives approval request

↓

Manager approves or rejects

↓

Employee receives notification

↓

Dashboard gets updated

---

## Technologies Used

Salesforce CRM
Lightning Web Components
Apex
SOQL
Flows
Approval Process
Reports & Dashboards
GitHub

## Reflection

Enterprise applications are not only about coding.

They require:

- Architecture Design
- Security Planning
- Approval Processes
- Scalability Considerations
- Failure Recovery
- Reporting & Analytics

This project helped me understand how Salesforce combines LWC, Apex, Flows, Approvals, and Reports to build a real-world enterprise solution.
