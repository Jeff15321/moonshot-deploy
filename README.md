# Getting Started

To get this project up and running on your local machine, follow these steps:

## Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14 or higher)  
- [Python](https://www.python.org/) (version 3.8 or higher)  
- [Pip](https://pip.pypa.io/en/stable/) (Python package manager)

---

## Installation

### 1. Clone the repository:

```bash
git clone https://github.com/<your-username>/<repo>.git
cd <repo>
2. Navigate to the backend directory and install the required Python packages:
bash
Copy code
cd backend
pip install -r requirements.txt
3. Navigate to the frontend directory and install the required Node.js packages:
bash
Copy code
cd frontend
npm install
Configuration
Create a .env file inside the backend directory and add your environment variables:

ini
Copy code
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
ANTHROPIC_API_KEY=your_anthropic_api_key
AZURE_STORAGE_CONNECTION_STRING=your_azure_storage_connection_string
If you do not require any of these services, you may safely omit unused variables.

Running the Application
Start the backend server:
bash
Copy code
cd backend
uvicorn app.main:app --reload
Start the frontend development server:
bash
Copy code
cd frontend
npm run dev
Once both servers are running, open your browser and navigate to:

http://localhost:5173

to view the application.
