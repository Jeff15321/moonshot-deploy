
Getting Started

To get this project running on your local machine, follow the setup instructions below.

Prerequisites

Make sure you have the following installed:

Node.js (version 14 or higher)

Python (version 3.8 or higher)

Pip (Python package manager)

Installation

Clone the repository:

git clone https://github.com/<your-username>/<repo>.git
cd <repo>


Navigate to the backend directory and install the required Python packages:

cd backend
pip install -r requirements.txt


Navigate to the frontend directory and install the required Node.js packages:

cd frontend
npm install

Configuration

Create a .env file inside the backend directory and add your environment variables:

SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
ANTHROPIC_API_KEY=your_anthropic_api_key
AZURE_STORAGE_CONNECTION_STRING=your_azure_storage_connection_string


If you do not require external services, you may skip any unused variables.

Running the Application

Start the backend server:

cd backend
uvicorn app.main:app --reload


Start the frontend development server:

cd frontend
npm run dev


Open your browser and go to:

👉 http://localhost:5173

to view the application.
