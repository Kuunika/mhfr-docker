# MHFR-DOCKER SETUP



## Dependencies

- Docker (>= 18)
- Docker Compose (>= 1.21.2)
- Git (>= 2.17.1)

## Instructions

1. ### Cloning the repository

   Clone the project to a directory of your choosing

   ```bash
   git clone https://github.com/Kuunika/mhfr-docker.git
   
   cd mhfr-docker
   ```

2. ### Configuring environment variables

   - Configure the container environment file

     ```bash
     cp .containers.env.example .containers.env
     ```

   - Configure the application(s) environment file 

     ```bash
     cp .env.example .env
     ```

3. ### Running the MHFR

   After that making the configurations, run the MHFR using the following command

   ```bash
   docker-compose up -d
   ```

   