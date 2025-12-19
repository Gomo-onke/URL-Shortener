# Cloud URL Shortener

A simple, scalable URL shortener built for cloud deployment with modern DevOps practices.

## Features
- RESTful API for URL shortening
- Web dashboard for URL management
- Auto-expiring URLs
- Click analytics
- Docker containerization
- Terraform infrastructure as code
- GitHub Actions CI/CD pipeline

## Tech Stack
- **Backend**: FastAPI (Python)
- **Frontend**: React.js
- **Database**: PostgreSQL
- **Infrastructure**: Terraform, Docker
- **Cloud**: AWS (EC2, RDS, S3)
- **CI/CD**: GitHub Actions

## Quick Start
```bash
# Clone repository
git clone https://github.com/yourusername/url-shortener.git
cd url-shortener

# Run with Docker Compose
docker-compose up -d

# Access the application
# Frontend: http://localhost:3000
# Backend API: http://localhost:8000
# API Docs: http://localhost:8000/docs
