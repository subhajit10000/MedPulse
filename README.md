# MedPulse

Doctor appointment booking: search doctors, pick a date and time slot, pay the fee online, manage appointments.

- `backend/` Express + MongoDB API (see its README)
- `frontend/` React + Vite + Tailwind

## Run locally
```
cd backend && npm install && cp .env.example .env   # fill in secrets
npm run seed && npm run dev
cd ../frontend && npm install && cp .env.example .env && npm run dev
```
Open http://localhost:5173. The backend's `CLIENT_URL` must match the frontend address exactly (use `localhost`, not `127.0.0.1`).
