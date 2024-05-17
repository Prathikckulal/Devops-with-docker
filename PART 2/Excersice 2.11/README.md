A basic Dockerfile was created to set up the backend service, and MongoDB was configured and linked to the backend service in the docker-compose.yml file.

# Install

 Clone the repository
   ```bash
   git clone https://github.com/GTS08/URL-Shortener-Microservice.git
   ```
 Go to project directory
   ```bash
   cd URL-Shortener-Microservice
   ```
 Move Dockerfile and docker-compose.yml into project directory
   ```bash
   cp ../Dockerfile ../docker-compose.yml .
   ```

 Run the following command.
   ```bash
   docker-compose up

