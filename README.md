## Team Management System | Desktop Application Case Study

## 📌 Project Overview

**Team Management System** is a high-performance desktop application developed with C# and WinForms during my studies at Information Technology Institute (ITI) in 2021. This repository serves as a Technical Case Study showcasing a secure, event-driven workflow for managing team tasks and sub-tasks in a Windows environment.

The application enables team leaders and administrators to create teams, assign tasks to members, track progress, and archive completed work - all within an intuitive Windows desktop interface.

---

## 🛠️ Technical Stack (Deep Dive)
- **Language:** C# (.NET Framework 4.5).
- **UI:** Windows Forms (WinForms).
- **Database:** SQL Server.
- **Patterns:** Object-Oriented Programming(OOP).
- **Communication:** Static Events & Actions for inter-form data synchronization.
- **Version Control:** Git & Github.

---

## 🚀 System Architecture & Workflow

### 1. Identity & Security (Screens 2, 3)
The system implements a secure **Registration and Login** flow with the following features:
- **Backend Validation:** All credentials are validated against SQL Server database
- **Encrypted Storage:** Passwords are securely stored using hashing algorithms

### 2. Resource Orchestration (Screens 4, 5)
Managers can establish their organizational structure by:
- **Creating Teams:** Define team name, type, and description
- **Onboarding Members:** Invite team members via email
- **Role Assignment:** Designate team leaders and members
- **Data Logic:** The system uses C# Lists and Classes to manage team entities before committing to the database

### 3. Task Management & Decomposition (Screens 7, 8)
This is the core of the application where tasks are created and broken down into **Sub-tasks**:
- **Hierarchical Task Structure:** Main tasks can contain multiple sub-tasks
- **Priority Management:** High, Medium, Low priority levels
- **Category Organization:** Tasks organized by categories (HR, Development, etc.)
- **Date Tracking:** Start date and end date for each task and sub-task
- **Status Tracking:** Finished/Unfinished status with checkbox functionality
- **Event Handling:** Uses static events to broadcast new tasks to the main workspace instantly
- **Real-time Updates:** Changes reflect immediately across all forms

### 4. Advanced Archiving & Data Recovery (Screen 6)
A sophisticated **Archive Module** handles the "Soft Delete" and "Restore" functionality:
- **Dual-Grid View:** Separates Archived Tasks from Archived Sub-tasks for better clarity
- **Soft Delete Pattern:** Archived items can be restored or permanently deleted
- **Clear All Function:** Bulk deletion capability
- **Decoupled Actions:** Uses static events to signal other forms to refresh data without tight coupling between windows
- **Data Integrity:** Maintains referential integrity between tasks and sub-tasks

## 📸 Visual Journey & Screenshots
*(All screenshots are organized in the [/Gallery](https://github.com/marwa-mahmoud3/Team-Management-System-CaseStudy/tree/main/Gallery) folder)*
1. **Main-Interface** - Welcome screen with creative illustrations showcasing teamwork and collaboration
2. **User-Registration** - Clean registration form with user icon, email, and password fields
3. **Login-Interface** - Secure login portal with "Sign Up" redirection for new users
4. **Team-Creation** - Intuitive team setup wizard with team type dropdown and description field
5. **Member-Onboarding** - Email-based member invitation system with visual appeal
6. **Archive-Management** - Professional archive view with tabular data presentation
7. **Task-Workspace.PNG** - Central command center displaying tasks, sub-tasks, and task details in a modal dialog
8. **Task-Creation-Wizard** - Sub-task creation interface with priority, dates, and finish status

---

## 🎯 Key Features & Functionality
✨ **Multi-User Environment**

- Support for multiple teams and team members
- Role-based access control (Admin/Leader vs. Member)

✨ **Comprehensive Task Management**

- Create, read, update, and archive tasks
- Hierarchical task breakdown (Tasks → Sub-tasks)
- Priority and category assignment
- Date range tracking

✨ **Real-Time Synchronization**

- Event-driven architecture ensures all forms stay updated
- Static events and actions prevent tight coupling
- Immediate UI refresh across multiple windows

✨ **Data Persistence & Recovery**

- SQL Server integration for reliable data storage
- Archive system with soft delete functionality
- Data restoration capabilities

✨ **User-Friendly Interface**

- Intuitive WinForms design with consistent styling
- Modal dialogs for focused task creation
- Visual feedback with custom illustrations
  
---

## 🎓 Educational Context

This project was developed during my intensive training program at the **Information Technology Institute (ITI)** in **2021** as part of the curriculum focused on:

- Desktop application development
- Database design and integration
- Object-oriented programming principles
- Software architecture patterns
- UI/UX design for Windows applications

The project demonstrates practical application of theoretical concepts learned during the program and showcases my ability to deliver a complete, functional software solution.

---

## 💡 Technical Highlights & Learning Outcomes

**Event-Driven Architecture**

- Implemented static events for decoupled inter-form communication
- Learned the importance of loose coupling in maintaining clean architecture

**Database Integration**

- Designed normalized database schema with proper relationships
- Implemented CRUD operations using ADO.NET
- Handled concurrent data access scenarios

**OOP Principles Applied**

- Encapsulation: Each form and class has well-defined responsibilities
- Inheritance: Base classes for common form functionality
- Polymorphism: Abstract methods for flexible task handling

**UI/UX Design**

- Created consistent visual language across all screens
- Implemented modal dialogs for better user focus
- Used intuitive icons and colors for improved usability

---

## 📺 Technical Walkthrough Video

For a complete demonstration of the application's features and functionality, watch the technical walkthrough:

https://github.com/user-attachments/assets/c33dd7e5-9d34-4955-90b2-07938810e821

---

## 🔒 Intellectual Property & Source Code

The source code is kept in a **Private Repository** to protect the intellectual property. This README serves as a **Technical Case Study** to demonstrate:

- System architecture and design decisions
- SQL Server integration capabilities
- C# and WinForms development proficiency
- UI design and user experience skills
- Problem-solving approach and technical documentation

**For recruiters and potential collaborators:** If you would like to review the source code or discuss the technical implementation in detail, please contact me directly.

---
## 👤 About the Developer

**Name:** Marwa Mahmoud Mohamed

**Email:** [marwa.sw.eng@outlook.com](mailto:marwa.sw.eng@outlook.com)

**Connect with me:**

- LinkedIn: [marwa-mahmoud123](https://www.linkedin.com/in/marwa-mahmoud123)
- Portfolio: [marwa-mahmoud-sw-eng.vercel.app](https://marwa-mahmoud-sw-eng.vercel.app/)

---

## 📄 License

This project is for educational and portfolio purposes. All rights reserved.

---

## 🙏 Acknowledgments

Special thanks to the **Information Technology Institute (ITI)** for providing comprehensive training in software development and the opportunity to build this project during the 2021 program.

---

*Built with passion during ITI training • Showcasing C# & SQL Server expertise • 2021*
