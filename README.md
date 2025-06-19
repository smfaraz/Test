Generated markdown
# AI-Powered Job Application Assistant

This is a web application designed to automate and personalize the job application process. It connects to a user's professional data, finds relevant job postings, and uses AI to generate personalized outreach emails to hiring managers.

This project is currently in the initial development phase, establishing the core full-stack architecture.

## Core Technologies

*   **Backend:** Python with **FastAPI**
*   **Frontend:** JavaScript with **React.js**
*   **Infrastructure:** **Docker** (to be implemented)
*   **AI:** Google's **Gemini** API (to be implemented)

## Current Status: Milestone 0 Complete

The foundational client-server architecture is complete and running.
*   A FastAPI backend server is running on port 8000.
*   A React frontend development server is running on port 3000.
*   The frontend successfully makes an API call to the backend.
*   CORS (Cross-Origin Resource Sharing) is correctly configured to allow communication between the frontend and backend.

## How to Run This Project

Follow these steps to get the development environment running on your local machine.

### Prerequisites

*   **Python 3.8+:** [Download Python](https://www.python.org/downloads/)
    *   *Make sure to check "Add Python to PATH" during installation.*
*   **Node.js and npm:** [Download Node.js](https://nodejs.org/) (npm is included)
*   **A Code Editor:** We recommend **VS Code** ([Download here](https://code.visualstudio.com/))

### 1. Backend Setup

First, we'll get the backend server running.

```bash
# 1. Navigate to the backend directory
cd backend

# 2. Create a Python virtual environment
# (You only need to do this once)
python -m venv venv

# 3. Activate the virtual environment
# On Windows (Command Prompt):
venv\Scripts\activate.bat
# On Windows (PowerShell):
.\venv\Scripts\Activate.ps1
# On Mac/Linux:
source venv/bin/activate

# 4. Install the required Python packages
# (The '(venv)' prefix should be visible in your terminal)
pip install "fastapi[all]"

# 5. Start the backend server
uvicorn main:app --reload
Use code with caution.
Markdown
Your backend is now running on http://127.0.0.1:8000. You can leave this terminal open.
2. Frontend Setup
Next, get the frontend React app running in a new, separate terminal.
Generated bash
# 1. Navigate to the frontend directory from the project root
cd frontend

# 2. Install the required Node.js packages
# (You only need to do this once)
npm install

# 3. Start the frontend development server
npm start
Use code with caution.
Bash
A new tab should automatically open in your browser to http://localhost:3000.
Expected Outcome
When both servers are running, the web page at http://localhost:3000 should display:
Frontend is Running!
Message from Backend: The backend is running!
This confirms that the entire stack is working correctly.
Next Steps
Milestone 1: Implement Docker and Docker Compose to manage the application stack with a single command.
Milestone 2: Add a PostgreSQL database for data persistence.
Milestone 3: Implement user authentication (registration and login).