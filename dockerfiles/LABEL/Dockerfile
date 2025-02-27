FROM almalinux:9
LABEL project="expense" \
      enviorment="dev" \
      component="frontend"
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]