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
git clone https://github.com/choprapranay/moonshot.git
cd moonshot
```
### 2. Navigate to the backend directory and install the required Python packages:
```bash
cd backend
python -m venv venv
source venv/Scripts/activate
pip install -r requirements.txt
```
### 3. Navigate to the frontend directory and install the required Node.js packages:
```bash
cd frontend
npm install
```
## Configuration
Create a .env file inside the backend directory and add your environment variables:
```
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key
```

Create a .env.local file inside the frontend directory and add your environment variables:
```
NEXT_PUBLIC_API_BASE_URL=http://127.0.0.1:8000
```

## Running the Application
Start the backend server:
```bash
cd backend
uvicorn app.main:app --reload
```
Start the frontend development server:
```bash
cd frontend
npm run dev
```
Once both servers are running, open your browser and navigate to `http://localhost:3000` to view the application.
