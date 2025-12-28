# AI Chatbot

A simple AI chatbot web application built with FastAPI and React.

## Prerequisites

- Node.js (v18+)
- Python (3.8+)
- OpenAI API Key

## Setup & Run

### 1. Backend

1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   # Windows:
   .\venv\Scripts\activate
   # Unix/MacOS:
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set your OpenAI API Key:
   - Rename `.env.example` to `.env` (or set the environment variable `OPENAI_API_KEY` directly).
   - Add your key to the file.

5. Start the server:
   ```bash
   uvicorn main:app --reload
   ```
   The backend will run at `http://localhost:8000`.

### 2. Frontend

1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```
   The frontend will typically run at `http://localhost:5173`.

## Usage

1. Open the frontend URL in your browser.
2. Type a message in the input box and press Send.
3. The chatbot will respond using OpenAI's API.
