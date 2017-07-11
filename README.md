# docker-compose NGINX maintenance page example

## Run:

    docker-compose up --force-recreate

## Test:
    
    curl localhost/
    Hello app!!
    docker-compose kill app
    curl localhost/
    Maintenance page
    docker-compose start app
    curl localhost/
    Hello app!!
