# azmat
django-svelte-saas-starter
# [Project Name]

![CI](https://img.shields.io/github/workflow/status/username/repo/CI)
![Django](https://img.shields.io/badge/Django-4.x-green)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue)
![Svelte](https://img.shields.io/badge/Svelte-4.x-orange)
![AWS](https://img.shields.io/badge/AWS-Deployed-yellow)

## 🎯 Overview
One-paragraph business problem + your solution approach.

## 🏗️ Architecture
[Insert simple diagram: SVG or PNG showing data flow]

**Stack:**
- Backend: Django + Django REST Framework + PostgreSQL + Celery
- Frontend: Svelte + Vite + Tailwind CSS
- Infrastructure: AWS EC2/RDS/S3, Docker, GitHub Actions

## ⚡ Key Decisions
| Decision | Rationale |
|----------|-----------|
| PostgreSQL over MySQL | ACID compliance, advanced JSONB queries, better Django ORM support |
| Svelte over React | Compile-time optimization, smaller bundle, better performance |
| REST + GraphQL | REST for CRUD, GraphQL for complex nested queries |
| AWS ECS + RDS | Managed infrastructure, auto-scaling, reduced ops overhead |

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- AWS CLI (configured)
- Node.js 18+

### Local Development
```bash
# Clone
git clone https://github.com/username/repo.git
cd repo

# Start services
docker-compose up -d

# Run migrations
docker-compose exec backend python manage.py migrate

# Seed data
docker-compose exec backend python manage.py loaddata fixtures.json

# Access
# Backend: http://localhost:8000
# Frontend: http://localhost:5173
