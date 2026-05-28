# WordPress + MySQL + phpMyAdmin with Docker Compose

A fully containerized WordPress stack with phpMyAdmin for database management.

## Services
- **WordPress** → http://localhost:8080
- **phpMyAdmin** → http://localhost:8081
- **MySQL 8.0** → internal only

## Getting Started

### 1. Clone the repo
git clone <your-repo-url>
cd my-wordpress

### 2. Create your .env file
cp .env.example .env

Then edit .env with your own passwords.

### 3. Start the stack
docker compose up -d

### 4. Stop the stack
docker compose down
