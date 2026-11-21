# Sustainfarm Web (React + Vite + Tailwind)

```powershell
npm install
npm run dev
```
Open the http://localhost:5173 link it prints.

To connect the backend, open `src/App.jsx`, find `const API_BASE_URL = '';` (about line 46) and set it to
`'http://localhost:8000'`, with the FastAPI server running (see sustainfarm-backend/README.md).
Leave it empty to run the frontend on its own.
