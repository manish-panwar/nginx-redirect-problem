- Building from Dockerfile:

    `docker build . -t custom-nginx`

- Running:

    `docker run -v ~/Downloads/nginx:/usr/share/nginx/html -v ~/Downloads/nginx/nginx.conf:/etc/nginx/nginx.conf  -p 8080:80ustom-nginx:latest`