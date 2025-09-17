nhat123.fun - starter project
=============================
Files:
- docker-compose.yml : run local with docker-compose up
- backend/ : Node.js API
- frontend/ : React + Vite frontend

Quick local dev (requires Docker):
1. Copy backend/.env.example to backend/.env and set JWT_SECRET.
2. Run: docker-compose up --build
3. Backend: http://localhost:4000
4. Frontend (dev): http://localhost:3000

Next steps for deployment:
- Create a GitHub repo and push backend & frontend.
- Deploy frontend to Vercel, backend to Render (or use a VPS).
- Create a managed Postgres (Render/Supabase) and update DATABASE_URL env.
- Point your domain nhat123.fun to the frontend host, and api.nhat123.fun to backend host.
