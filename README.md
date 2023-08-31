# Django & React application

### This Project is:

- Authentication (register and login). REST and React
- CRUD operations on the enterprise model and filtering the enterprises. REST
- Following and listing of follow-ups. REST and React
-

## ![Django](https://github.com/abdullah-algumar/DRFAuthFilter)

## ![React](https://github.com/abdullah-algumar/ReactApp)

# Install and Run

### Install main Repo: 
`gi clone https://github.com/abdullah-algumar/DjangoAndReactApp.git`

### Install React & Django repos:
`git submodule update --init --recursive`

### Create a environment file in the BASE_DIR named .env and put the informations:

```
touch .env
```

```
DEBUG=True
SECRET_KEY=<secret-key>
POSTGRES_DB=<db-name>
POSTGRES_USER=<db-user>
POSTGRES_PASSWORD=<db-password>
DATABASE_HOST=<db-host>
DATABASE_PORT=5432
```

# Run with Docker

## on the main folder of project run this command

`docker-compose up -d --build`

# Running

- http://127.0.0.1:8866 is the Django app
- http://127.0.0.1:3000 is the React app
