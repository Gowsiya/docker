ARG version
FROM almalinux:${version:-9}
ARG USERNAME=Gowsiya
ENV USERNAME=${USERNAME:-some_user}
RUN echo "Hi, ${USERNAME}" > /tmp/hello.txt
CMD ["sleep", "100"]