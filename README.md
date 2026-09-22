# Chat Realtime API

Realtime chat backend built with FastAPI, WebSocket, PostgreSQL and Redis.

## Stack

- **Language:** Python 3.12
- **Framework:** FastAPI
- **ORM:** SQLAlchemy 2.0 (async)
- **Database:** PostgreSQL
- **Cache / Pub-Sub:** Redis
- **Auth:** JWT
- **Testing:** pytest, pytest-asyncio, httpx
- **Linting:** ruff, mypy
- **Package manager:** uv

## Status

🚧 In development. Sprint 0: project setup.

## Quickstart

Instructions will be added in Sprint 5.

## Tests

Instructions will be added in Sprint 5.

## Project structure

app/
├── api/ # HTTP and WebSocket endpoints
├── core/ # Config, security, shared utilities
├── db/ # Database session and connection
├── models/ # SQLAlchemy models
├── schemas/ # Pydantic schemas
├── services/ # Business logic
└── tests/ # Test suite

## License

MIT