# PRODIGY_BD_02

## Task 02 - Persistent Storage with Database Integration

This project is part of my **Backend Web Development Internship** at **Prodigy InfoTech**.

### Project Description

This project extends a basic REST API by integrating a **MySQL** database for persistent data storage using **Django ORM**. It supports complete CRUD operations on a user resource and uses environment variables for secure configuration.

### Features

- Create a user
- Retrieve all users
- Retrieve a user by ID
- Update a user (PUT/PATCH)
- Delete a user
- MySQL database integration
- Django ORM
- Database migrations
- Environment variable configuration
- Input validation and error handling

### Technologies Used

- Python
- Django
- Django REST Framework
- MySQL
- PyMySQL

### API Endpoints

| Method | Endpoint |
|--------|----------|
| GET | `/api/users/` |
| POST | `/api/users/` |
| GET | `/api/users/<uuid:user_id>/` |
| PUT | `/api/users/<uuid:user_id>/` |
| PATCH | `/api/users/<uuid:user_id>/` |
| DELETE | `/api/users/<uuid:user_id>/` |

---

**Internship:** Prodigy InfoTech  
**Track:** Backend Web Development  
**Task:** PRODIGY_BD_02
