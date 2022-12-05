# Laravel-Devcontainer-scaffold
Files for a VSCode devcontainer using Laravel.

Project scaffold was created via Laravel Sail in WSL. `curl -s "https://laravel.build/example-app?with=mysql,redis&devcontainer" | bash`.
This command creates a laravel devcontainer using mysql and redis.

Other available services include mysql, pgsql, mariadb, redis, memcached, meilisearch, minio, selenium, and mailhog.

### Configuration
All of the configuration files for the Laravel framework are stored in the `config` directory.

Environment configuration is setup in the `.env` file. These include items such as DB connection and setup used by docker-compose, app configuration, and environment variables for other selected services.