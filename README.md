# lav

Backend API for lav

## Tech Stack

- **Frontend**: React
- **Backend**: FastAPI + SQLAlchemy
- **Frontend Source**: GitHub ([Repository](https://github.com/HimaShankarReddyEguturi/Designecommerceproductui.git))

## Project Structure

```
lav/
├── frontend/          # Frontend application
├── backend/           # Backend API
├── README.md          # This file
└── docker-compose.yml # Docker configuration (if applicable)
```

## Getting Started

### Prerequisites

- Node.js 18+ (for frontend)
- Python 3.11+ (for Python backends)
- Docker (optional, for containerized setup)

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
# Follow backend-specific setup instructions in backend/README.md
```

## Features

- User authentication and authorization
- Resource management (CRUD operations)
- Profile management

## API Endpoints

- `POST /api/register` - Create a new user account.
- `POST /api/login` - Log in to the application.
- `POST /api/password_reset` - Reset user password.
- `GET /api/profile` - Get user profile information.
- `PUT /api/profile` - Update user profile information.
- `GET /api/resources` - Get a list of available resources.
- `GET /api/resources/{resource_id}` - Get details of a specific resource.
- `POST /api/resources` - Create a new resource.
- `PUT /api/resources/{resource_id}` - Update an existing resource.
- `DELETE /api/resources/{resource_id}` - Delete a resource.

## License

MIT
