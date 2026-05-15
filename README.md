# NetManage

NetManage is a small Jira-like task manager for a university full-stack project. In later phases it will support users, projects, members, assigned tasks, priorities, and a Kanban board with Todo, Started, Testing, Finishing, and Done statuses.

## Stack

- Frontend: Next.js, TypeScript, Tailwind CSS
- Backend: ASP.NET Core Web API, C#
- Database: MongoDB
- Backend database access: MongoDB.Driver
- Future authentication: JWT
- Development target: local only

## Folder Structure

```text
NetManage/
  backend/
    NetManage.Api/
  frontend/
  env.example
  COMMAND.txt
  README.md
```

## Run Backend

```powershell
cd .\backend\NetManage.Api
dotnet restore
dotnet run
```

Backend Swagger runs at:

```text
http://localhost:5000/swagger
```

Health endpoint:

```text
http://localhost:5000/api/health
```

## Run Frontend

```powershell
cd .\frontend
npm install
npm run dev
```

Frontend runs at:

```text
http://localhost:3000
```

## Local URLs

- Frontend: http://localhost:3000
- Backend Swagger: http://localhost:5000/swagger
- Health endpoint: http://localhost:5000/api/health

MongoDB must be running locally for later phases.
