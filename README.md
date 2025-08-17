# Amazon (GRP Project for CBA India Internship)

This is a full-stack e-commerce clone project built as a group (GRP) project for the CBA India Internship.

## Structure
- `backend/` — Node.js/Express API (no MongoDB required for mock/demo mode)
- `frontend/` — React app (connects to backend via proxy)

## Quick Start (Windows)
1. Clone/download this repo.
2. Run the provided PowerShell script:

```powershell
./start-all.ps1
```

This will open two terminals: one for the backend (http://localhost:5000), one for the frontend (http://localhost:3000).

## Manual Start
- Backend:
  ```powershell
  cd backend
  npm install
  node server.js
  ```
- Frontend:
  ```powershell
  cd frontend
  npm install
  npm start
  ```

## Notes
- If you want to use a real MongoDB, set `MONGO_URL` in `backend/.env` and restart the backend.
- For demo/mock mode, no database is required.

## Project Screenshots

*Add your project screenshots here to showcase the application features:*

- Homepage
  <img width="1888" height="920" alt="Screenshot 2025-08-17 214807" src="https://github.com/user-attachments/assets/4c8c6876-2ea1-4693-a46e-ad17308e7e53" />
- Product listings
  <img width="1889" height="914" alt="pic2" src="https://github.com/user-attachments/assets/7db26b06-e644-4ba8-bde5-d24a7336f5ff" />
- Dark Mode
  <img width="1886" height="920" alt="darkmode" src="https://github.com/user-attachments/assets/2562f56c-4baa-4993-b91e-f22bcaacaf53" />

---
**Project for CBA India Internship (GRP)**
