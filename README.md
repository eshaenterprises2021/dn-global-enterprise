# DN Global Technology — Enterprise MVP

Starter MVP for a custom enterprise management platform.

## Stack
- Frontend: React + TypeScript + Vite
- Backend: ASP.NET Core 8 Web API
- Database: PostgreSQL
- API style: REST
- Authentication: planned for Phase 2

## MVP modules
- Dashboard
- Customers
- Leads
- Tasks
- Basic reporting

## Run locally

### Backend
```bash
cd backend
dotnet restore
dotnet run
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

The frontend expects the API at `http://localhost:5000`.
