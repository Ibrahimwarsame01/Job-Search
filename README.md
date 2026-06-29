# Job Search

A real-time tech job search website built with HTML, CSS, JavaScript, Node.js, PostgreSQL, and Docker.

## What it does

- Search for tech jobs in real time using the Remotive API
- Filter by job level, location, and time posted
- Results cached in a PostgreSQL database
- Clean light/dark mode UI

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js + Express |
| Database | PostgreSQL |
| Job Data | Remotive API |
| Containerization | Docker |

## Folder StructureJ

ob-Search/

├── docker-compose.yml

├── .env

├── backend/

│   ├── Dockerfile

│   ├── server.js

│   ├── db.js

│   └── routes/

│       ├── jobs.js

│       └── search.js

└── frontend/

├── index.html

├── style.css

└── app.js

## Getting Started

### Prerequisites
- Node.js installed
- Docker Desktop installed

### Installation

1. Clone the repo
```bash
git clone https://github.com/Ibrahimwarsame01/Job-Search.git
cd Job-Search
```

2. Create your `.env` file
```bash
cp .env.example .env
```

3. Start with Docker
```bash
docker-compose up
```
4. Open your browser


## Roadmap

- [x] Project setup
- [x] Folder structure
- [ ] Frontend UI
- [ ] Backend API
- [ ] PostgreSQL integration
- [ ] Docker setup
- [ ] AI job matching (Claude API)

## Author

Ibrahim Warsame — [@Ibrahimwarsame01](https://github.com/Ibrahimwarsame01)

