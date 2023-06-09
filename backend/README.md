# CarPartFinderPro

A web platform for posting car part listings, with a focus on parts for imported American cars and vehicles with hard-to-find parts.

## Project Goals:

1. **What are we creating?** - A web platform that allows users to post listings for car parts.
2. **Why are we creating this?** - To increase the availability of parts for imported American cars and vehicles with hard-to-find parts.
3. **How are we creating this?**:
    - a) Initial technology stack: Django - Python, Vue.js, PostgreSQL.
    - b) Diagramming tools for creating team workflows and user application use-case scenarios.
    - c) Task tracking tools such as Trello.

## Project Authors:

- Wiktoria Kuprańska
- Hubert Fijołek
- Albert Jurasik

---

## Workflow:

### How to start the project on a local machine:
1. `git clone` - clone the repository
2. `pip install -r requirements.txt` - install the required packages

### Branches:
- Use `frontend-branch` for frontend-related file modifications.
- Use `backend-branch` for backend-related file modifications.

### Synchronize between branches:
1. `git fetch` - to find new branches
2. `git checkout -b <branch-name> origin/<branch-name>` - to add a branch locally and synchronize

### Migrations:
1. `python manage.py makemigrations` - create new migrations
2. `python manage.py migrate` - apply the migrations

### Generate and load fixtures:
1. `python manage.py load_fixtures` - load the fixtures
