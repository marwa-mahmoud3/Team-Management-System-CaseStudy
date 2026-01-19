# Team Management System | Desktop Application Case Study

## 📌 Project Overview
**Team Management System** is a high-performance desktop application developed with **C# and WinForms**. This repository serves as a **Technical Case Study** showcasing a secure, event-driven workflow for managing team tasks and sub-tasks in a Windows environment.

## 🛠️ Technical Stack (Deep Dive)
- **Language:** C# (.NET Framework 4.5).
- **UI:** Windows Forms (WinForms).
- **Database:** SQL Server.
- **Patterns:** Object-Oriented Programming.
- **Communication:** Static Events & Actions for inter-form data synchronization.

## 🚀 System Architecture & Workflow

### 1. Identity & Security (Screens 2, 3)
The system implements a secure **Registration and Login** flow.
- **Backend:** Data is validated against an SQL Server database.

### 2. Resource Orchestration (Screens 4, 5)
Managers can establish their organizational structure by **Creating Teams** and **Onboarding Members**.
- **Data Logic:** The system uses C# Lists and Classes to manage team entities before committing to the database/UI.

### 3. Task Management & Decomposition (Screens 7, 8)
This is the core of the application where tasks are created and broken down into **Sub-tasks**.
- **Task Logic:** allowing managers to assign priorities and deadlines.
- **Event Handling:** Uses to broadcast new tasks to the main workspace instantly.

### 4. Advanced Archiving & Data Recovery (Screen 6)
A sophisticated **Archive Module** handles the "Soft Delete" and "Restore" functionality.
- **Dual-Grid View:** Separates Main Tasks from Sub-tasks for better clarity.
- **Decoupled Actions:** Uses static events like to signal other forms to refresh data without tight coupling between windows.

## 📸 Visual Journey
*(All screenshots are organized in the [/Gallery](/Gallery) folder)*
1. **Registration:** Secure onboarding with data validation.
2. **Login:** Database-verified access control.
3. **Team Setup:** Creating the project's human infrastructure.
4. **Members:** Assigning roles within the team.
5. **Archive:** A showcase of data preservation and recovery logic.
6. **Workspace:** Central hub for monitoring active tasks.
7. **Main Task:** Defining core project objectives and priorities.
8. **Sub-tasks:** Granular task breakdown and member assignment.

## 📺 Technical Walkthrough
https://github.com/user-attachments/assets/1f74f685-ef59-45cd-b9b7-5429a791aa35

---
## 🔒 Intellectual Property
The source code is kept in a **Private Repository**. This Case Study highlights architecture, SQL integration, and UI design skills.

---
**Developed by [Your Name]**
