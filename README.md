

# PSTORE

A full-stack e-commerce project built with Postgres, Express, React and Node.

## Swagger API Documentation

[Documentation](https://pstore.onrender.com/api/docs/)

## Demo

[Run demo](https://pstore.netlify.app)



## Database Schema

[![ERD](https://user-images.githubusercontent.com/51405947/133893279-8872c475-85ff-47c4-8ade-7d9ef9e5325a.png)](https://dbdiagram.io/d/5fe320fa9a6c525a03bc19db)

## Run Locally

Clone the project

```bash
  git clone https://github.com/puko2/PStore.git
```

Go to the project directory

```bash
  cd PERN-Store
```

Install dependencies

```bash
  npm install
```

Go to server directory and install dependencies

```bash
  npm install
```

Go to client directory and install dependencies

```bash
  npm install
```

Go to server directory and start the server

```bash
  npm run dev
```

Go to client directory and start the client

```bash
  npm run client
```

Start both client and server concurrently from the root directory

```bash
  npm run dev
```

## Running with docker

Make sure you have Docker installed

### Run the development environment

```bash
docker-compose -f docker-compose.dev.yml up
```

### Run the production environment

```bash
docker-compose up
```

Go to http://localhost:3000 to view the app running on your browser.

## Deployment

To deploy this project run

```bash
  npm run deploy
```


## Environment Variables

To run this project, you will need to add the following environment variables to your .env files in both client and server directory

#### client/.env

`VITE_GOOGLE_CLIENT_ID`

`VITE_GOOGLE_CLIENT_SECRET`

`VITE_API_URL`

`VITE_STRIPE_PUB_KEY`

### server/.env

`POSTGRES_USER`

`POSTGRES_HOST`

`POSTGRES_PASSWORD`

`POSTGRES_DATABASE`

`POSTGRES_DATABASE_TEST`

`POSTGRES_PORT`

`PORT`

`SECRET`

`REFRESH_SECRET`

`SMTP_FROM`

`STRIPE_SECRET_KEY`


