# WP Devbox

Built with [Docker Compose and WordPress](https://docs.docker.com/samples/wordpress/).

## How to use it
1. Check the environment variables in [the .env file](https://docs.docker.com/compose/environment-variables/#the-env-file). Keep them or change them as desired; _the defaults should only be used in a development environment_. Additional environment variables for WordPress can be added to [WORDPRESS_CONFIG_EXTRA](https://github.com/docker-library/wordpress/pull/142).
2. Run `docker-compose up`. WordPress files will be stored in `wordpress/` and MySQL data will be stored in `mysql/`. Git will ignore both of these, and deleting them will remove all data and require repeating this step.
3. Visit [http://localhost:8000] in a web browser to complete the installation.
