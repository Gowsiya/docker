From almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/Gowsiya/docker/refs/heads/main/dockerfiles/FROM/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp
#COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]