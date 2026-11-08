# IT Help Desk Management System

A full-stack web application designed to streamline IT support operations by centralizing incident reporting, ticket management, technician assignments, and issue resolution.

## About the Project

The IT Help Desk Management System is a web-based application that helps organizations manage internal IT support requests efficiently.

Employees can submit support tickets, describe technical issues, and track their requests. IT technicians can review incidents, assess their severity, manage assigned tickets, and document solutions. Administrators can oversee users, technicians, ticket assignments, and overall support activities.

The project aims to simulate a real-world IT service desk environment while applying modern full-stack development practices.

## Project Objectives

- Build a functional and user-friendly IT support platform.
- Implement role-based access control.
- Develop a structured ticket management workflow.
- Practice REST API development and database integration.
- Apply software engineering principles to a practical business scenario.

## Planned Features

### 1. User Authentication and Authorization
- User registration and login.
- Secure authentication.
- Role-based access control.
- Three user roles: Employee, Technician, and Administrator.

### 2. Ticket Management
- Create, view, update, and manage support tickets.
- Categorize technical incidents.
- Set suggested and official ticket priorities.
- Track ticket status and resolution progress.
- Attach relevant files or screenshots.

### 3. Technician Management
- Assign tickets to technicians.
- Reassign unresolved tickets when necessary.
- Track technician workload.
- Maintain intervention history.

### 4. Administrative Dashboard
- Monitor all support tickets.
- Manage employees and technicians.
- Track incident priorities and statuses.
- View support activity statistics.

### 5. Knowledge Base
- Document recurring technical issues.
- Store troubleshooting procedures and solutions.
- Organize technical documentation for future reference.

### 6. Activity Tracking
- Maintain a history of important ticket updates.
- Track status and priority changes.
- Record technician interventions.

## Technology Stack

**Frontend**
- React
- Vite
- JavaScript
- CSS
- React Router

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB
- Mongoose

**Development Tools**
- Git and GitHub
- Visual Studio Code
- Postman

## Project Structure

The application will follow a modular architecture separating frontend components, backend logic, and database models.

```text
help-desk-management-system/
├── client/
│   ├── src/
│   └── public/
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── config/
│
└── README.md
```

## Development Roadmap

- [ ] Project setup and initial configuration
- [ ] Frontend interface and navigation
- [ ] Dashboard and ticket management interface
- [ ] Backend API development
- [ ] MongoDB database integration
- [ ] Authentication and authorization
- [ ] Ticket assignment and workflow management
- [ ] Knowledge base implementation
- [ ] Testing and debugging
- [ ] Application deployment

## Project Status

**Currently in development.**

Features and documentation will be updated as the project progresses.

## Author

**Stephie Ngaleu**

Computer Programming Graduate | Aspiring Full-Stack Developer

GitHub: [@stephDurelle](https://github.com/stephDurelle)

---

This project is developed as part of my ongoing journey in full-stack software development, with a focus on building practical applications and strengthening my technical skills.
