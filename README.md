🏥 Hospital Billing Portal
A role-based Hospital Billing Portal built with React (frontend), Node.js + Express (backend), and MySQL (database) using Docker for containerization.
This system supports multiple user roles (User, Patient, Doctor, Staff, Accountant), role-specific dashboards & reports, and authentication via Google or Mobile Number.


🚀 Tech Stack
Frontend: React.js, React Router, Axios
Backend: Node.js, Express.js
Database: MySQL (Dockerized)
Authentication: Google OAuth, Mobile OTP (future)
Containerization: Docker & Docker Compose
Version Control: Git + GitHub


📂 Project Structure

hospital-billing-portal/
│── docker-compose.yml          
│── README.md
│── .gitignore
│
├── backend/                    # Node.js API
│   ├── src/
│   │   ├── config/             # DB & auth configs
│   │   ├── routes/             # API endpoints
│   │   ├── controllers/        # Business logic
│   │   ├── models/             # DB models
│   │   ├── middleware/         # Auth & role checks
│   │   └── utils/              # Helpers
│
├── frontend/                   # React App
│   ├── public/
│   └── src/
│       ├── pages/              # Public & dashboards
│       ├── components/         # Reusable UI
│       ├── services/           # API calls
│       ├── context/            # Auth & state
│       └── styles/             # CSS
│
├── db/                         # Database scripts
│   ├── init.sql
│   └── seed.sql
│
└── docs/                       # Documentation
    ├── roadmap.md
    ├── architecture.md
    └── api-spec.md







📌 Features (Planned)
✅ Public pages (Home, News, Contact, Scheme)
✅ Login/Signup (Google, Mobile number)
✅ Role-based dashboards (User, Patient, Doctor, Staff, Accountant)
✅ Role-specific reports (summary/dashboard)
🔜 Billing & invoice management
🔜 Staff management & schedules
🔜 Analytics & admin dashboard


🛣 Roadmap (Phase 0 → Phase 6)
Phase 0 → Requirements, DB design, folder setup, Docker skeleton
Phase 1 → Authentication system (Google, Mobile)
Phase 2 → Role-based dashboards & routing
Phase 3 → Reports per user type
Phase 4 → Billing workflows
Phase 5 → UI/UX enhancements
Phase 6 → Deployment



👨‍💻 Author
Aryan J.
Hospital Billing Portal Project (Learning + Development).