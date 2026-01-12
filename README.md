# Pet E-commerce API

RESTful API for pet products e-commerce platform with authentication and layered architecture.

**Author**: [Andrey Quesada](https://github.com/andreyques41) | Software Engineer | Full-Stack Development & AI Workflows

---

## Stack

**Backend**: Flask, PostgreSQL, SQLAlchemy, JWT  
**Testing**: Pytest (806 tests, 78% coverage)  
**Docs**: OpenAPI

---

## Features

- User authentication and authorization (JWT)
- Product catalog management
- Shopping cart operations
- Order processing workflow
- Invoice generation
- Returns system
- Layered architecture (controllers/services/repositories)
- 42 REST endpoints

---

## Architecture

```
Routes → Controllers → Services → Repositories → Models
```

**Key Patterns**:
- Repository pattern for data access
- Service layer for business logic
- Marshmallow for validation
- Role-based access control

---

## Quick Start

```bash
pip install -r requirements.txt
flask run
```

---

## What This Demonstrates

- RESTful API design principles
- JWT authentication and authorization
- Multi-layer validation (schema, business, database)
- PostgreSQL with SQLAlchemy ORM
- Comprehensive testing strategies
- Clean architecture patterns

---

**GitHub**: [andreyques41/pet-ecommerce-api](https://github.com/andreyques41/pet-ecommerce-api)
