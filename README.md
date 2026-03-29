# DBInspect CLI

> Database inspection CLI with schema diff and query runner

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
Rust, Clap, SQLite

## 🏗️ Architecture
Backend service with Rust, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/dbinspect-cli
cd dbinspect-cli

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
