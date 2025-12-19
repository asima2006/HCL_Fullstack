# Healthcare Wellness Portal

A MERN stack application for patients and healthcare providers to manage wellness goals, appointments, and preventive care compliance.

## Tech Stack

- **Frontend:** React.js/Next.js, Axios, CSS Modules
- **Backend:** Node.js, Express.js, JWT authentication, bcrypt
- **Database:** MongoDB with Mongoose ODM
- **Deployment:** AWS/GCP/Vercel, Docker, GitHub Actions

## Features

**Patients:**
- Track wellness goals and compliance status
- Book appointments with providers
- View health profile and reminders

**Providers:**
- Monitor assigned patients
- Set and track patient goals
- Manage availability

## Quick Start

```bash
# Backend
cd backend
npm install
cp .env.example .env  # Configure your environment
npm run dev

# Frontend
cd frontend
npm install
npm start
```

## API Routes

| Route | Description |
|-------|-------------|
| `POST /api/auth/register` | User registration |
| `POST /api/auth/login` | User login |
| `GET /api/patients/goals` | Get patient goals |
| `POST /api/patients/appointments/book` | Book appointment |
| `GET /api/providers/patients` | Get assigned patients |

## Entity Relationship Diagram

![ER Diagram](image.png)

## Security

- JWT-based authentication with role-based access control
- Password hashing with bcrypt
- HIPAA-compliant audit logging
- HTTPS enforcement and CORS protection

## License

MIT
