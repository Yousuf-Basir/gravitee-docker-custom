This repo is made by following [Custom Install with Docker Compose](https://documentation.gravitee.io/apim/getting-started/install-guides/install-on-docker/custom-install-with-docker-compose) and it solves the issue of nginx log permission.

Copy `./.env.example` as `./.env` file and change `ADDRESS` to your IP address especially if you use a real IP address to solve connecting with `8083` port

# Run docker compose
Run docker compose to download and start all of the components.
> docker compose -f docker-compose-apim.yml up -d

In your browser, go to http://YOURIPADDRESS:8084 to open the Console, and go to http://YOURIPADDRESS:8085 to open the Developer Portal. You can log in to both with the username admin and password admin.
