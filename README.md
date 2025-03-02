# Soma.AI

![Soma.AI Logo](https://see.fontimg.com/api/rf5/2aB3/NzU3OGMwMzhjZjJkNGI2NzhhNGM4OTNiMmQ0ZDg3MzEub3Rm/U29tYS5haQ/alien-league-ii-3d.png?r=fs&h=33&w=1250&fg=000000&bg=FFFFFF&tb=1&s=26)

## Transforming Corporate Learning with AI

Soma.AI is an innovative Learning Management System (LMS) designed specifically for corporate environments. By leveraging advanced artificial intelligence, our platform streamlines the learning process and automates material creation, empowering educators to design high-quality, personalized content with unprecedented ease.

## 🚀 Project Overview

Soma.AI was born out of the need for a corporate-focused LMS that addresses the limitations of existing solutions. After auditing traditional platforms like Inform LMS and Skool, we identified numerous pain points including dark UX patterns, confusing navigation, and limited collaboration features.

Our solution combines enhanced versions of essential LMS features with innovative new capabilities to create a comprehensive, user-friendly platform tailored for modern corporate learning environments.

## ✨ Key Features

- **AI-Powered Content Creation**: Automate the generation of learning materials, quizzes, and assessments
- **Personalized Learning Paths**: Customized experiences based on individual progress and learning styles
- **Robust Collaboration Tools**: Seamless interaction between educators, learners, and content creators
- **Advanced Course Management**: Intuitive tools for organizing and delivering educational content
- **Engaging Quiz System**: Interactive assessment tools that go beyond basic multiple-choice formats
- **Modern, User-Friendly Interface**: Clean design that prioritizes usability and engagement

## 🛠️ Tech Stack

### Frontend
- **Next.js**: React framework for building the user interface
- **TypeScript**: For type-safe code
- **TailwindCSS**: For responsive and customizable styling
- **Redux**: State management
- **Jest & React Testing Library**: For comprehensive testing

### Backend
- **Django**: High-level Python web framework
- **Django REST Framework**: For building the API
- **PostgreSQL**: Primary database
- **Celery**: Task queue for background processes
- **Redis**: Caching and message broker

### DevOps
- **Docker**: Containerization for consistent development and deployment
- **Docker Compose**: Multi-container orchestration
- **GitHub Actions**: CI/CD pipelines
- **Nginx**: Web server and reverse proxy

## 🏗️ Architecture

The application follows a microservices architecture with:

1. **Client Application**: Next.js frontend serving the user interface
2. **API Service**: Django backend providing RESTful endpoints
3. **Authentication Service**: Handling user identity and access management
4. **Content Service**: Managing learning materials and course content
5. **Analytics Service**: Tracking user progress and system performance

## 🚦 Getting Started

### Prerequisites
- Docker and Docker Compose
- Node.js (v14+)
- Python (v3.8+)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/mont3ll/AI-Powered-Learning-Platform.git
cd AI-Powered-Learning-Platform
```

2. Start the development environment:
```bash
docker-compose up -d
```

3. The application will be available at:
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:8000/api
   - Admin panel: http://localhost:8000/admin

### Development Workflow

#### Frontend Development
```bash
cd frontend
npm install
npm run dev
```

#### Backend Development
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## 📝 API Documentation

API documentation is available at `/api/docs/` when running the backend server. We use Swagger UI for interactive API exploration.

## 🧪 Testing

### Frontend Tests
```bash
cd frontend
npm test
```

### Backend Tests
```bash
cd backend
python manage.py test
```

## 🔄 CI/CD Pipeline

Our CI/CD pipeline includes:

1. Automated testing for both frontend and backend
2. Code quality checks using ESLint, Prettier, and Black
3. Automated Docker image building
4. Deployment to staging and production environments

## 📅 Project Timeline

- **Week 1-4**: Initial development and MVP
- **Week 5-7**: Beta testing and feature refinement
- **Week 8**: Public release and ongoing improvements

## 📚 Documentation

Additional documentation:
- [User Guide](./docs/user-guide.md)
- [Admin Guide](./docs/admin-guide.md)
- [Developer Guide](./docs/developer-guide.md)
- [API Reference](./docs/api-reference.md)

## 👥 Contributors

Our amazing team:
- Montell Luseno
- Newton Luttah
- Kenneth Kimutai
- Rihaz Yusuf

## 📄 License

This project is licensed under the [MIT License](LICENSE)

## 🤝 Contact

For questions or support, please contact:
- Email: support@soma-ai.com
- Website: https://soma-ai.com
