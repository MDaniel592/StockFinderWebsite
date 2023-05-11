# StockFinderWeb
  **Doc in progress**
  
This is the root repository containing the backend and frontend

## Backend (Flask + Gunicorn)

For updating the requirements, use: pipreqs --encoding=utf8 --force

### Development
You can start the backend in development runnnig 'flask run' inside flask_back directory
- Important -> Make sure there is NO telegram=0.0.1 defined on requirements and gunicorn==20.0.1 is defined.

### Production
Build Dockerfile and start the container (use the docker-compose and fill out all the environment variables)



## Frontend (NextJS)

You can start the frontend in development runnnig 'npm run dev' inside nextjs_front directory

### Production
Build Dockerfile and start the container (use the docker-compose and fill out all the environment variables)