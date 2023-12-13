Introducing Nginx

- [ ] Getting started with Docker and Nginx
    - [x] Pull image from Docker
    - [x] Run Nginx container

          `docker run -it --rm -d -p 8080:80 --name website nginx`

    - [x] Docker stop container
    - [ ] Verifying your installation
        - [x] Nginx -v
        - [x] Docker top web
        - [x] curl localhost
        - [x] Browser localhost:8080
    - [ ] Basic Service management
        - [x] service nginx start
        - [x] service nginx stop
        - [ ] Nginx commands
            - [x] -h
            - [x] -v -V
            - [x] -t -T
            - [x] -s signal

                ```
                  -V            : show version and configure options then exit
                  -t            : test configuration and exit
                  -T            : test configuration, dump it and exit
                ```
                
    - [x] Nginx default folder /usr/share/nginx/html
    - [x] Docker-compose file - using volumes
    - [x] Serving custom pages - index.html
    - [x] Building a new Nginx image
        - [x] DockerFile

