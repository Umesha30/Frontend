# Servigo Admin Dashboard Frontend

## Project Overview

Servigo Admin Dashboard is a web-based administration platform developed for managing users, workers, services, bookings, reviews, revenue, and overall system operations of the Local Service Marketplace Platform.

This project is developed using React.js, JavaScript, Tailwind CSS, React Router DOM, Axios, Vite, Git, and GitHub.

---

# Tech Stack

* React.js
* JavaScript (ES6+)
* Tailwind CSS
* React Router DOM
* Axios
* Vite
* Git & GitHub
* npm (Node Package Manager)

---

# Prerequisites

Before starting development, ensure the following software is installed:

* Node.js (Latest LTS Version)
* npm
* Visual Studio Code
* Git

Check installed versions:

```bash
node -v
npm -v
git --version
```

---

# Project Setup

Clone the repository:

```bash
git clone <repository-url>
cd servigo-admin
```

Install project dependencies:

```bash
npm install
```

Start development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview production build:

```bash
npm run preview
```

---

# Project Structure

```text
src
├── components
├── pages
├── layouts
├── services
├── hooks
├── utils
├── modules
│   ├── dashboard
│   ├── users
│   ├── services
│   ├── bookings
│   ├── revenue
│   └── settings
```

---

# Folder Descriptions

### components/

Reusable UI Components

Examples:

* Button
* Input
* Navbar
* Sidebar
* Modal
* Table

### pages/

Authentication and common pages

Examples:

* Login
* Signup
* OTP Verification
* Forgot Password

### layouts/

Shared layouts

Examples:

* DashboardLayout

### services/

API-related services

Examples:

* authService.js
* bookingService.js
* userService.js

### hooks/

Custom React Hooks

Examples:

* useAuth
* useUsers
* useBookings

### utils/

Utility and helper functions

Examples:

* formatDate
* constants
* validation

### modules/

Feature-based application modules

---

# Member Responsibilities

## Member 1 – Authentication & Core UI System

Responsible for:

* Login Page
* Sign Up Page
* Forgot Password Page
* OTP Login
* OTP Verification
* Role Selection
* Dashboard Layout
* Sidebar Navigation
* Navbar/Header
* Reusable Components

  * Button
  * Input
  * Modal
  * Table

Assigned Folders:

```text
components/
pages/
layouts/
hooks/
```

---

## Member 2 – Dashboard Overview & System Statistics

Responsible for:

* Dashboard Homepage
* Statistics Cards
* Revenue Charts
* Booking Charts
* Activity Feed
* Analytics Widgets

Assigned Folder:

```text
modules/dashboard/
```

---

## Member 3 – User Management

Responsible for:

* User List
* Search Users
* Filter Users
* User Profiles
* Complaint Handling

Assigned Folder:

```text
modules/users/
```

---

## Member 4 – Worker Management & Settings

Responsible for:

* Worker Verification
* Worker Profiles
* Worker Ratings
* System Settings

Assigned Folder:

```text
modules/settings/
```

---

## Member 5 – Service & Category Management

Responsible for:

* Service Management
* Category Management
* Add/Edit/Delete Services
* Service Status Management

Assigned Folder:

```text
modules/services/
```

---

## Member 6 – Bookings, Reviews & Revenue

Responsible for:

* Booking Management
* Booking Details
* Reviews & Ratings
* Revenue Analytics
* Reports

Assigned Folders:

```text
modules/bookings/
modules/revenue/
```

---

# Branch Names

| Member   | Branch Name              |
| -------- | ------------------------ |
| Member 1 | member1-auth-ui          |
| Member 2 | member2-dashboard        |
| Member 3 | member3-users            |
| Member 4 | member4-settings         |
| Member 5 | member5-services         |
| Member 6 | member6-bookings-revenue |

---

# Route Names

```text
/login
/signup
/forgot-password
/otp-login
/verify-otp
/role-selection

/dashboard
/users
/services
/bookings
/revenue
/settings
```

---

# React.js Development Standards

* Use Functional Components only.
* Use React Hooks.
* Follow component reusability principles.
* Keep business logic separate from UI.
* Follow feature-based architecture.
* Use React Router DOM for navigation.

Example:

```jsx
function Login() {
  return <div>Login Page</div>;
}

export default Login;
```

---

# React Hooks Guidelines

Recommended Hooks:

* useState
* useEffect
* useContext
* useMemo
* useNavigate

Custom Hooks:

```text
hooks/
├── useAuth.js
├── useUsers.js
└── useBookings.js
```

---

# Tailwind CSS Guidelines

* Use Tailwind CSS for all styling.
* Avoid inline CSS.
* Follow reusable utility classes.
* Maintain responsive design.
* Support Desktop, Tablet and Mobile views.

Example:

```jsx
<button className="bg-green-700 text-white px-4 py-2 rounded-lg">
  Login
</button>
```

---

# Package Management

Install packages using npm.

Examples:

```bash
npm install axios
npm install react-router-dom
```

Install all project dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev  
    or
npm strat
```

Build project:

```bash
npm run build
```

---

# Coding Standards

### Naming Convention

Components:

```text
Navbar.jsx
Sidebar.jsx
Button.jsx
Input.jsx
Modal.jsx
```

Pages:

```text
Login.jsx
DashboardPage.jsx
UsersPage.jsx
ServicesPage.jsx
BookingsPage.jsx
RevenuePage.jsx
SettingsPage.jsx
```

### File Naming

* Use PascalCase for Components and Pages.
* Use camelCase for utility files and hooks.

Examples:

```text
useAuth.js
formatDate.js
constants.js
```

---

# Git Workflow

Before starting work:

```bash
git pull origin main
```

Create or switch to assigned branch:

```bash
git checkout member-branch-name
```

After completing work:

```bash
git add .
git commit -m "Completed feature"
git push
```

Create a Pull Request before merging to the main branch.

---

# Team Workflow

1. Clone the repository.
2. Install dependencies using npm install.
3. Switch to your assigned branch.
4. Develop only the assigned module.
5. Commit changes regularly.
6. Push changes to GitHub.
7. Create a Pull Request.
8. Team Leader reviews the code.
9. Merge approved changes into main.

---

# Important Notes

* Do not modify another member's module without permission.
* Follow the folder structure strictly.
* Keep code clean and reusable.
* Follow React.js and Tailwind CSS best practices.
* Test all pages before pushing changes.
* Maintain consistent UI design across the project.
