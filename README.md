# Advanced Web Development (AWD) Practicals

This repository contains the complete practical assignments and full-stack projects for the Advanced Web Development Frameworks (AWDF) laboratory curriculum.

## 📁 Repository Structure

| Directory | Practical Description | Tech Stack |
| :--- | :--- | :--- |
| `practical1` | Student Portfolio Web Application | React, Vite, CSS |
| `practical2` | Multi-page Navigation & Routing | React Router, Vite |
| `practical3` | Asynchronous Data Fetching & API Integration | React, Axios, REST API |
| `practical4` | State Management & Context API | React Context, Hooks |
| `practical5` | Custom Hooks & Performance Optimization | React, Hooks |
| `practical6` | Express.js RESTful API Backend | Node.js, Express.js |
| `practical7` | Database Integration & CRUD Operations | Node.js, Express.js, MongoDB / Mongoose |
| `practical8` | Full-Stack Integration (Frontend + Backend) | React, Express.js, MongoDB |
| `practical9` | User Authentication & Authorization | JWT, bcrypt, Express Middleware |
| `practical10` | Request Validation, Middleware & Error Handling | Express.js, Joi / Zod |
| `practical11` | Automated Testing & Quality Assurance | Jest, Supertest, React Testing Library |
| `practical12` | Containerization & Continuous Integration | Docker, Docker Compose, GitHub Actions |
| `practical13` | Full-Stack Production Deployment | Full-Stack (MERN) Architecture |

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- npm or yarn
- MongoDB (local instance or MongoDB Atlas connection string)
- Docker & Docker Compose (for practical 12/13)

### Running a Practical
Each practical contains dedicated subdirectories for `frontend` and/or `backend` where applicable:

```bash
# Example: Running Practical 12 Frontend
cd practical12/frontend
npm install
npm run dev

# Example: Running Practical 12 Backend
cd practical12/backend
npm install
npm start
```

## 🔄 CI/CD Pipeline
Continuous Integration is configured via GitHub Actions in [`.github/workflows/ci.yml`](.github/workflows/ci.yml) to automatically validate frontend builds, test suites, and Docker configurations.
