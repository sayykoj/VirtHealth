You need 3 separate Command Prompt windows:

**Window 1 - Backend (Port 5000):**
cd BACKEND
npm start
Leave this window open and running.
________________________________________

**Window 2 - Frontend (Port 5173):**
Open a NEW Command Prompt window:
cd frontend
npm start
Leave this window open and running.
________________________________________

**Window 3 - AI Model (Port 8000):**
Open ANOTHER Command Prompt window:
cd BACKEND\ai-model
python -m uvicorn main:app --reload --port 8000
Leave this window open and running.
________________________________________

Quick way to open multiple Command Prompts:
1. Press Windows Key
2. Type cmd
3. Press Enter
4. Repeat 3 times to get 3 windows
