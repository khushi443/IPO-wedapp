## 🚀 Deployment Technical Documentation

### Backend (Django)
- Deployed on Render
- PostgreSQL used as DB
- JWT authentication implemented

### Frontend (React)
- Deployed on Netlify
- Connected using Axios to the backend

### API Endpoints:
- `/api/ipos/` – List IPOs
- `/api/ipos/<id>/` – IPO Detail
- `/api/token/` – JWT Login
- `/api/token/refresh/` – Token Refresh

### Testing
- CRUD operations tested via React
- Auth tested via Postman and React frontend
