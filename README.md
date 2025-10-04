# CodeCrew

# ExpenseSync: Hackathon Submission
Project for: Odoo
Challenge: Advanced Expense Management System
Submitted By: Code Crew

Hello Review Team,

Welcome to the repository for ExpenseSync, our submission for the Odoo hackathon. This project is a functional prototype designed as a comprehensive solution to the expense management challenge provided.

Our goal was to build a clean, intuitive, and interactive user interface that demonstrates the core functionalities and user flows for a multi-role expense approval system.

The Challenge: Problem Statement
The hackathon challenge was to design a system to replace time-consuming, error-prone, and non-transparent manual expense reimbursement processes. The key requirements were to build a platform that could handle:

Multi-level approval workflows.

Flexible and conditional approval rules.

Distinct roles and permissions for Employees, Managers, and Administrators.

Our Solution & Approach
To address this, we developed a high-fidelity, interactive prototype. Our approach was to create a complete application experience using client-side JavaScript and localStorage to manage application state and simulate data persistence. This enabled us to focus on creating a seamless and user-friendly experience for all three required roles within the hackathon timeframe.

✅ Key Features Implemented
We successfully implemented the following features based on the problem statement:

User Roles & Authentication:

Role-based access with distinct dashboards for Admins, Managers, and Employees.

Simulated user persistence using browser localStorage.

Employee Dashboard (employee.html):

At-a-glance summary of expense statuses (Draft, Pending, Approved).

Intuitive modal for creating and submitting new expenses.

Ability to save multiple expenses as drafts and submit them in a single batch.

Manager Dashboard (manager.html):

A dedicated approval queue showing all pending expenses from the team.

A detailed view for each expense, providing all necessary context for a decision.

Functional "Approve" and "Reject" actions that update the expense status in the UI.

Admin Dashboard (admin.html):

A high-level overview of system-wide metrics.

A User Management interface to simulate adding, editing, and assigning roles.

A mock interface for configuring Approval Rules.

