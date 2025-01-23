# Career Connect

## Overview
The **Career Connect Project** is a full-stack web application built using the MERN stack (MongoDB, Express, React, Node.js). It provides a platform where recruiters can post job openings and candidates can search, browse, and apply for jobs.

---

## Features

### User Roles
- **Recruiters**:
  - Post and manage job listings.
  - View and manage company profiles.
- **Candidates**:
  - Browse and search for jobs.
  - Apply for job postings.
  - Manage their profile and applications.

### Functionalities
- **Authentication**:
  - User login and signup (JWT-based authentication).
  - Role-based access control.
- **Job Management**:
  - Post, edit, and delete job listings (for recruiters).
  - Search and filter jobs (for candidates).
- **User Profiles**:
  - Create and update user profiles.
  - Profile photos and bios for personalization.
- **Responsive Design**:
  - Fully responsive UI for desktop and mobile users.
- **Logout**:
  - Secure logout functionality.

---

## Technologies Used

### Frontend
- **React.js**: For building the user interface.
- **TailwindCSS**: For responsive and modern styling.
- **React Router**: For routing and navigation.

### Backend
- **Node.js**: For building the server-side logic.
- **Express.js**: For creating RESTful APIs.
- **MongoDB**: For database storage.
- **Mongoose**: For database modeling and interaction.

### Additional Tools
- **Redux**: For state management.
- **Axios**: For API calls.
- **Render**: Backend deployment.

---

## Installation and Setup

### Prerequisites
- Node.js installed on your system.
- MongoDB installed locally or a MongoDB Atlas account.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd job-portal-project
   ```

2. **Install Dependencies**:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. **Environment Variables**:
   Create a `.env` file in the `server` directory with the following keys:
   ```env
   PORT=5000
   MONGO_URI=<your-mongodb-connection-string>
   JWT_SECRET=<your-jwt-secret>
   ```

4. **Run the Application**:
   - Start the server:
     ```bash
     cd server
     npm start
     ```
   - Start the client:
     ```bash
     cd client
     npm start
     ```

5. **Access the Application**:
   Open your browser and navigate to `http://localhost:3000`.

---

## Screenshots

Include relevant screenshots to showcase the application:
1. **Landing Page**
2. **Job Listings**
3. **Recruiter Dashboard**
4. **Candidate Profile**

---

## Deployment

The backend has been deployed using Render. To deploy the client and server, follow these steps:

1. **Client Deployment**:
   - Use services like Vercel or Netlify.
   - Update the API base URL in the client code.

2. **Backend Deployment**:
   - Use platforms like Render or Heroku.
   - Ensure environment variables are correctly set.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact
For any queries, reach out to:
- **Name**: Digesh Dansana
- **Email**: [digeshdansana@gmail.com]
- **LinkedIn**: [www.linkedin.com/in/digesh-dansana]

---
