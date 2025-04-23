# Event Manager Project

## 🔧 About the Project

A secure REST API for managing users and events, built with FastAPI, SQLAlchemy, and tested using pytest. Supports JWT-based OAuth2 authentication and role-based access control.

---

## ✅ Closed Issues

Here are five issues I resolved during this assignment:

1. [Fix JWT token validation](https://github.com/TheJenniferAponte/event_manager_project/issues/1)
2. [Test locked user access](https://github.com/TheJenniferAponte/event_manager_project/issues/2)
3. [Fix email test failure by mocking SMTP](https://github.com/TheJenniferAponte/event_manager_project/issues/3)
4. [Add missing schema fields to test_user_update_valid](https://github.com/TheJenniferAponte/event_manager_project/issues/4)
5. [Fix 401 unauthorized admin access](https://github.com/TheJenniferAponte/event_manager_project/issues/5)

Each issue contains a description of the bug or missing test and is linked to the commit that resolved it.

---

## 🐳 Docker Image

Project Docker Image: [docker.io/jenniferaponte/event-manager](https://hub.docker.com/repository/docker/jenniferaponte/event-manager)

---

## 📘 Reflection

This onboarding project helped me strengthen my skills in:

- **Writing and organizing tests** using `pytest`, including async client tests and schema validation.
- **Debugging access issues and JWT token logic**, which deepened my understanding of OAuth2 flows.
- **Mocking external services** like SMTP to test email flows without relying on external servers.
- **Schema validation** using Pydantic, including how test fixtures reflect model structures.

On the collaboration side, I learned how to **track progress with GitHub issues**, link them to code, and write clearer documentation to communicate intent. This workflow prepares me to work more effectively in collaborative and production environments.
