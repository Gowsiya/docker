From almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/Gowsiya/docker/blob/main/dockerfiles/FROM/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD sample-.tar /tmp
#COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]