Table of Contents
What the project does
Why the project is useful
How users can get started with the project
Where users can get help with your project
Who maintains and contributes to the project

DOCKER SETUP 
    --- To get latest app version run:

    --- To spin up docker docker use:
        $ docker-compose up -d

    --- To enter MYSQL container run:
        In MySQL conainer data is keept under /var/lib/mysql dir (initialy around 250MB) you can map this directory as volume or create other direcotry for dump sql file and presists only sql dump files (save space).

        !Note - to log in to mysql use credentail from .env file (you can change them there)
        $ docker exec -it mymysql-con bash

    --- To do change APACHE CONFIG go to this dir
        This direcotry is mounted to a volume in docker-compose.yaml

APP SETUP
    --- ...
