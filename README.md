# Shams Academy School of Inventors

An interactive online learning platform focused on teaching innovative thinking and inventive skills.

## Project Structure

```
.
├── frontend/               # React.js frontend application
├── backend/               # Django Rest Framework backend
└── docker/                # Docker configuration files
```

## Technology Stack

### Frontend
- React.js
- Redux for state management
- Material-UI/Tailwind CSS for styling
- Axios for API requests
- React Router for routing

### Backend
- Django Rest Framework
- PostgreSQL database
- JWT authentication
- Celery for asynchronous tasks
- Redis for caching

### DevOps
- Docker & Docker Compose
- Nginx as reverse proxy
- PostgreSQL for database

## Features

- User Authentication with email verification
- Interactive course platform (free & paid courses)
- Payment integration (Payme, Click, Uzum)
- Forum and discussion system
- Comprehensive admin panel
- User profiles and course tracking

## Getting Started

### Prerequisites
- Docker and Docker Compose
- Node.js (for local development)
- Python 3.8+ (for local development)

### Development Setup
1. Clone the repository
2. Copy environment files:
   ```bash
   cp frontend/.env.example frontend/.env
   cp backend/.env.example backend/.env
   ```
3. Start the development environment:
   ```bash
   docker-compose up --build
   ```

### API Documentation
API documentation is available at `/api/docs/` when running the backend server.

## Contributing
Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details.