# Finance-Hub Project

## Overview
Finance-Hub is a full-stack application designed to manage savings plans, user authentication, feedback, and plan applications. It consists of an Angular frontend and a .NET backend, providing a robust platform for financial management.

---

## Project Structure

- **angularapp/**: Angular 8+ SPA for user interaction and management.
- **dotnetapp/**: ASP.NET Core backend API for business logic and data persistence.
- **TestProject/**: Unit tests for backend services and controllers.

---

## Key Features

### 1. User Authentication
- Secure login and registration (JWT-based).
- Role-based access (User, Manager).
- AuthGuard for route protection in Angular.

### 2. Savings Plan Management
- Create, edit, and delete savings plans (Manager role).
- Apply for savings plans (User role).
- Validation and error handling for plan operations.

### 3. Feedback System
- Users can submit feedback.
- Managers can view and respond to feedback.

### 4. Application Tracking
- Users can track the status of their savings plan applications.
- Managers can approve or reject applications.

### 5. Error Handling
- Custom exceptions in backend (e.g., PlanAlreadyExistsException).
- Angular error components for user-friendly messages.

---

## Technology Stack

- **Frontend**: Angular, TypeScript, RxJS, Angular Material
- **Backend**: ASP.NET Core, Entity Framework Core, SQL Server
- **Testing**: Jasmine/Karma (Angular), xUnit (C#)

---

## Folder Highlights

### angularapp/src/app/components
- Modular components for login, home, manager dashboard, savings plan management, feedback, error handling, etc.

### angularapp/src/app/services
- Service classes for API communication (Auth, SavingsPlan, Feedback, etc.).

### dotnetapp/Controllers
- RESTful controllers for authentication, feedback, plan applications, and savings plans.

### dotnetapp/Models
- Entity models for users, plans, feedback, and applications.

### dotnetapp/Services
- Business logic for authentication, feedback, plan management.

---

## Security & Best Practices
- JWT authentication and authorization.
- Input validation and error handling.
- Separation of concerns (services, controllers, models).
- Unit testing for critical backend logic.

---

## How to Run

1. **Backend**: 
   - Navigate to `dotnetapp/` and run `dotnet run`.
2. **Frontend**: 
   - Navigate to `angularapp/` and run `npm install` then `ng serve`.

---

## Future Enhancements
- Add more granular user roles.
- Implement email notifications.
- Enhance UI with more analytics and charts.
- Expand test coverage.

---

## Authors & Contributors
- Project Lead: [Your Name]
- Contributors: [List of team members]

---

## License
Specify your project license here.

---

## Contact
For queries or support, contact jayasuryapanduru7@gmail.com.
