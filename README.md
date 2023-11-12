# WordPress Docker Container

1. Clone the repo
2. copy .env-dist to .env
3. Define variable values according to your need
4. ```docker-compose up -d --build```

## New Wordpress
**APPLICATION_VOLUME:** Define variable and live folder emprty. A new wordpress 
will be installed.

## Existing Wordpress
**APPLICATION_VOLUME:** Map the folder containing Wordpress project to the variable.