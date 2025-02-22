# Job Portal - MERN Stack Application

This is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack, designed to streamline the job application process for both applicants and recruiters.

## Features

**General:**

* **User Roles:** Clear distinction between applicant and recruiter roles.
* **Account Management:** User registration and login functionality.
* **Persistent Sessions:** Sessions remain active after login.
* **Authentication & Authorization:** Secure REST APIs with JWT (JSON Web Tokens).

**Recruiter Features:**

* **Job Management:** Create, update, and delete job postings.
* **Application Management:** Shortlist, accept, or reject job applications.
* **Resume Viewing:** Access and review applicant resumes.
* **Profile Management:** Update recruiter profile information.

**Applicant Features:**

* **Job Search:** Search for jobs with filtering options.
* **Job Application:** Apply to jobs with a Statement of Purpose (SOP).
* **Application Tracking:** Monitor the status of submitted applications.
* **Profile Management:** Upload profile picture and resume, and update profile details.

## Technologies Used

* **Frontend:**
    * React.js
    * HTML5
    * CSS3
    * Javascript
* **Backend:**
    * Node.js
    * Express.js
* **Database:**
    * MongoDB
* **Authentication:**
    * JWT (JSON Web Tokens)

## Getting Started

### Prerequisites

* Node.js and npm (Node Package Manager)
* MongoDB installed and running

### Installation

1.  **Clone the repository:**

    ```bash
    git clone <repository_url>
    ```

2.  **Navigate to the backend directory:**

    ```bash
    cd backend
    ```

3.  **Install backend dependencies:**

    ```bash
    npm install
    ```

4.  **Create a `.env` file in the backend directory and add your MongoDB connection string and JWT secret:**

    ```
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

5.  **Start the backend server:**

    ```bash
    npm start
    ```

6.  **Navigate to the frontend directory:**

    ```bash
    cd ../frontend
    ```

7.  **Install frontend dependencies:**

    ```bash
    npm install
    ```

8.  **Create a `.env.local` file in the frontend directory and add your backend API URL:**

    ```
    REACT_APP_API_URL=http://localhost:5000/api
    ```

    (Replace `http://localhost:5000/api` with your actual backend API URL if different.)

9.  **Start the frontend application:**

    ```bash
    npm start
    ```

10. Open your browser and navigate to `http://localhost:3000`.

