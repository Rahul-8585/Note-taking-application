# Full-Stack Note-Taking App

A modern note-taking application built with the MERN stack (MongoDB, Express, React, Node.js) and TypeScript.

## Features

-   User signup with Email/OTP and Google OAuth.
-   Secure authentication using JWT.
-   Create and delete personal notes.
-   Fully responsive design.

## Technology Stack

-   **Frontend:** React, TypeScript, Vite, Axios, Tailwind CSS
-   **Backend:** Node.js, Express, TypeScript, Mongoose
-   **Database:** MongoDB Atlas
-   **Deployment:** Vercel (Frontend), Render (Backend)

## Setup and Installation

### Prerequisites

-   Node.js (v18.x or later)
-   npm or yarn
-   Git

### Backend Setup

1.  Clone the repository: `git clone <your-repo-url>`
2.  Navigate to the backend directory: `cd note-app-backend`
3.  Install dependencies: `npm install`
4.  Create a `.env` file in the root of the backend directory and add the following variables:
    ```
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_super_secret_key
    PORT=5001
    GOOGLE_CLIENT_ID=your_google_client_id
    GOOGLE_CLIENT_SECRET=your_google_client_secret
    ```
5.  Start the development server: `npm run dev`

### Frontend Setup

1.  Navigate to the frontend directory: `cd note-app-frontend`
2.  Install dependencies: `npm install`
3.  Create a `.env.local` file in the root of the frontend directory and add the following:
    ```
    VITE_API_BASE_URL=http://localhost:5001
    ```
4.  Start the development client: `npm run dev`

## Live URL

-   **Frontend:** [Your Deployed Frontend URL]
-   **Backend API:** [Your Deployed Backend URL]
