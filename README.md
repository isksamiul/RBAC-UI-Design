# User Management System with Role-Based Access Control (RBAC)

A user-friendly **Role-Based Access Control (RBAC)** application built with **React-JS**, designed for seamless management of users and roles. This application provides a robust interface for adding, editing, and deleting users and roles, with data persistence powered by **localStorage**. The project is styled with **Tailwind CSS**, ensuring a responsive design for both desktop and mobile platforms.

---

## 📌 Features

### **User Management**
- **Add Users:** Add new users with their name, email, and assigned role using a clean, intuitive form. Email validation ensures data accuracy.
- **Edit Users:** Modify existing user details by pre-filling a form with their current data.
- **Delete Users:** Permanently remove users from the system via the "Delete" button.

### **Role Management**
- Create and assign roles to users. Roles define access levels, supporting future scalability and permission-based control.

### **Data Persistence**
- All user and role data are saved in **localStorage**, ensuring:
  - Data is retained across page refreshes.
  - A seamless user experience without the need for a backend.

### **Responsive Design**
- Tables and forms are designed to adapt gracefully to various screen sizes, ensuring usability on both desktop and mobile devices.

---

## 🛠️ Technologies Used

- **React:** Dynamic and responsive UI development.
- **Tailwind CSS:** Modern styling for responsiveness and aesthetics.
- **localStorage:** Client-side storage for persistent user and role data.

---

## 🚀 Getting Started

### Prerequisites
- Ensure **Node.js** and **npm** are installed on your system.

### Installation and Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/isksamiul/RBAC-UI-Design.git
2. **Navigate to the Project Directory:**

   ```bash
   cd RBAC-UI-Design
3. **Install Dependencies:**

   ```bash
   npm install
4. **Start the Application:**

   ```bash
   npm start
The application will run locally and can be accessed at http://localhost:3000


## 💡 How to Use

1. **Role Management:**
   - Begin by creating roles to assign to users.
   - Roles determine user access and permissions.

2. **Adding Users:**
   - Click the **"Add User"** button.
   - Fill out the form with user details, including their name, email, and role.
   - Ensure the email is in the correct format before saving.

3. **Editing Users:**
   - Locate a user in the table and click the **"Edit"** button.
   - A form with the user’s current details will appear. Modify the details as needed.
   - Save the changes to update the user’s information.

4. **Deleting Users:**
   - Click the **"Delete"** button next to a user’s record in the table.
   - Confirm the deletion to permanently remove the user from the system.

5. **LocalStorage:**
   - The application uses **localStorage** to save user and role data.
   - All changes, such as adding, editing, or deleting data, are saved locally.
   - Data persists across page reloads and is retrieved automatically when the app loads.
---
## 🖼️ Screenshots

### Dashboard View
The main dashboard displays a table of users with their name, email, role, and status. You can add, edit, or delete users directly from this view.

<p align="center">
  <img src="Assets\User.png" width="45%" />
  <img src="Assets\Role.png" width="45%" />
</p>


### Add/Edit User Form
A clean and intuitive form is used to add or edit user details such as name, email, role, and status.

<p align="center">
  <img src="Assets\Adduser.png" width="45%" />
  <img src="Assets\Edituser.png" width="45%" />
  <img src="Assets\Addrole.png" width="45%" />
  <img src="Assets\Editrole.png" width="45%" />
</p>


### Responsive Design
The application adjusts seamlessly to different screen sizes, ensuring usability on both desktop and mobile devices.

<p align="center">
  <img src="Assets\Res.png" width="60%" />
</p>


---

## 📂 Folder Structure

The project is organized into the following structure for better maintainability and scalability:


### Key Directories and Files:
- **`components/`**: Contains reusable UI components like forms and tables.
- **`pages/`**: Contains higher-level views like the Dashboard.
- **`styles/`**: Includes custom styles or configurations for Tailwind CSS.
- **`App.js`**: Serves as the main entry point for rendering the application’s components.
- **`localStorage`**: User and role data are stored here via the browser.

This structure ensures clean code organization, making the app easy to scale and maintain.
