# Setting Up a Modern NodeJS Development Environment with Docker

## Requirements

* [Docker](https://docs.docker.com/get-docker/)
* [Docker Compose](https://docs.docker.com/get-docker/)

## Installation Steps (if applicable)

1. Install Docker
2. Open a terminal in the folder you want to store your website in (use _File_ > _Open Powershell_ on windows to open PowerShell in the currently opened folder)
3. Clone project https://github.com/usukesh28/nodejs-docker-tutorial.git
4. Build image `docker build . -t <your username>/node-web-app`
5. Run image `docker run -p 49160:8080 -d <your username>/node-web-app`
5. Navigate to <http://localhost:8080>

## Further help

To get more help on the Docker follow https://nodejs.org/en/docs/guides/nodejs-docker-webapp/

## License

Code examples are licensed under the MIT license.
