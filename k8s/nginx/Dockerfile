# Source: https://www.docker.com/blog/how-to-use-the-official-nginx-docker-image/
# Additional: https://www.bluematador.com/blog/building-and-deploying-to-kubernetes
FROM nginx:latest
# Here we set our custom nginx.conf file to be loaded as the default one 
COPY ./nginx.conf /etc/nginx/conf.d/default.conf