# Project Management Tool (MERN)

## Overview

This full-stack project management application, built on the MERN stack (MongoDB, Express.js, React, Node.js), is designed to streamline team collaboration and project monitoring. It empowers users to manage tasks, delegate team roles, track project progress, and communicate in real time.

## Benefits of Using This App

In fast-paced work environments, managing tasks effectively is essential for team success. Relying on spreadsheets or manual tracking can be inefficient and error-prone. The MERN-based Project Management Application delivers several key benefits for development teams and end users, including:

1. **User Authentication:**
   - Register and log in using email or social media accounts.
   - Enjoy role-based access control (e.g., Admin, User, Project Manager).

2. **Project Dashboard:**
   - Create, view, and manage multiple projects.
   - Monitor project statistics such as task progress and deadlines.

3. **Task Management:**
   - Create tasks and assign them to team members.
   - Organize tasks with priority settings and labels.

4. **Collaboration Tools:**
   - Comment on individual tasks.
   - Share files within task discussions.
   - Receive real-time updates on task modifications.

### Detailed Features

#### *Admin Capabilities:*

1. **User Management:**
   - Establish admin accounts.
   - Add and oversee team members.

2. **Task Assignment:**
   - Allocate tasks to one or more users.
   - Update task details and status as needed.

3. **Task Properties:**
   - Categorize tasks as "to do," "in progress," or "completed."
   - Set priority levels (high, medium, normal, low).
   - Create and manage subtasks.

4. **Asset Management:**
   - Upload assets such as images for tasks.

5. **User Account Control:**
   - Activate or disable user accounts.
   - Permanently delete or temporarily remove tasks.

#### *Core Application Features:*

1. **Authentication and Authorization:**
   - Secure sign-up and login using JWT (JSON Web Tokens).
   - Implement role-based access control (Admin, Manager, Member).

2. **Project Creation and Management:**
   - Initiate new projects, assign team members, and set deadlines.
   - Get a comprehensive project overview, including milestones and progress tracking.

3. **Task Management:**
   - Add, update, or remove tasks within projects.
   - Assign due dates and priorities to tasks for efficient tracking.

4. **Real-Time Collaboration:**
   - Leverage WebSockets (Socket.io) for live updates on project and task changes.
   - Receive notifications for task updates, project modifications, and approaching deadlines.

5. **Team Management:**
   - Add, remove, or edit team members within projects.
   - Allocate distinct roles (Admin, Project Manager, Developer, etc.).
   - Manage role-based permissions for accessing tasks, projects, and team settings.

#### *Technologies Utilized:*

1. **Fundamental Technologies:**
   - **HTML5:** Structures content and defines the overall layout.
   - **CSS3:** Styles visual elements including layout, colors, fonts, and responsiveness.
   - **JavaScript (ES6+):** Drives interactivity and dynamic user interactions.

2. **Frontend Frameworks and Libraries:**
   - **React.js:** Facilitates the creation of user interfaces with a component-based architecture.
     - **State Management:** Utilizes Context API or Redux for global state management.
     - **React Hooks:** Manages state and lifecycle functions in functional components.

3. **UI Libraries:**
   - **Tailwind CSS:** Provides a utility-first approach for rapid component styling.

4. **State Management:**
   - **Redux:** Handles complex application state, especially in React apps (e.g., user data, tasks, project milestones).

5. **Routing and Navigation:**
   - **React Router:** Manages navigation between different pages and views.

6. **API Integration:**
   - **Axios:** A promise-based HTTP client for communicating with the backend API.
   - **Fetch API:** Native browser API used for making HTTP requests.

The Cloud-Based Task Manager is an innovative solution that enhances team efficiency and organization. By leveraging the MERN stack along with modern frontend technologies, this platform ensures a seamless experience for both administrators and users, ultimately boosting collaboration and productivity.

## Setup Instructions

### Server Setup

#### Environment Variables

Begin by creating an `.env` file in the server folder. This file should include:

- `MONGODB_URI` = your MongoDB URL
- `JWT_SECRET` = a secure secret key
- `PORT` = 8800 (or any other port)
- `NODE_ENV` = development

#### Setting Up MongoDB

1. **MongoDB Atlas Setup:**
   - Visit the [MongoDB Atlas website](https://www.mongodb.com/cloud/atlas).
   - Create and log in to your MongoDB Atlas account.
   - Create a new cluster by selecting a cloud provider and region.
   - Configure the cluster settings and deploy it.
   - Create a database user and configure the IP whitelist.
   - Connect your application to the cluster by updating the `.env` file with your MongoDB connection URL.
   - Test the connection to ensure everything is set up correctly.

#### Running the Server

1. Open the project in your preferred code editor.
2. Navigate to the server directory:
   ```bash
   cd server
   ```
3. Install the required packages:
   ```bash
   npm install
   ```
4. Start the server:
   ```bash
   npm start
   ```
If configured correctly, a message confirming the server is running and the database is connected should appear.

### Client Setup

1. Navigate to the client directory:
   ```bash
   cd client
   ```
2. Install the necessary packages:
   ```bash
   npm install
   ```
3. Launch the application:
   ```bash
   npm start
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

This rephrased overview captures the complete functionality and setup of the project management tool built using the MERN stack.
