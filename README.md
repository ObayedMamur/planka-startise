# Planka
#### Elegant open source project tracking.

## Development Setup

### Environment Variables
Ensure the following environment variables are set in your Docker configuration in `docker-compose-dev.yml`:

- `NODE_ENV=development` for all services to run in the development mode.
- `DEFAULT_ADMIN_EMAIL=demo@demo.demo` - Email address for the admin account.
- `DEFAULT_ADMIN_PASSWORD=demo` - Password for the admin account.
- `DEFAULT_ADMIN_NAME=Demo Demo` - Full name of the admin.
- `DEFAULT_ADMIN_USERNAME=demo` - Username for the admin login.

### For First Time Setup Run this command only:
```sh
docker compose -f docker-compose-dev.yml up --build
```

### Run This Command to start the development environment every time:
```sh
docker compose -f docker-compose-dev.yml up -d
```

See the official [development section](https://docs.planka.cloud/docs/Development).

## Tech stack

- React, Redux, Redux-Saga, Redux-ORM, Semantic UI React, react-beautiful-dnd
- Sails.js, Knex.js
- PostgreSQL

## License

Planka is [AGPL-3.0 licensed](https://github.com/plankanban/planka/blob/master/LICENSE).
