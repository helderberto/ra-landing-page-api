# React Avançado - Landing Page API

## Requirements

- [Docker](https://www.docker.com/)

## How to Run

- Download images from Docker for Strapi and Postgres `docker-compose pull`
- Run project with the downloaded images `docker-compose up`

## Troubleshooting

Executing the dump database into Docker:

```bash
cat ~/ra-landing-page-api/dump/strapi.sql | docker exec -i <CONTAINER_NAME> psql -U <USERNAME> -d <DB_NAME>
```

## Resources

- [Official Repository](https://github.com/React-Avancado/landing-page-api)
