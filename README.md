# Connecting pg_cron to postgres 17 via Docker Compose

1. First, install pg_cron with your PostgreSQL 17 Docker image.
2. After installation, run the following commands to clean up:
   docker-compose down
   docker volume ls
   docker volume rm <volume_name>  # Be cautious! This will remove data.
   
4. docker-compose up --build
5. CREATE EXTENSION pg_cron;
