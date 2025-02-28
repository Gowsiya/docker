ARG version
FROM almalinux:${version:-9}
ARG USERNAME
ENV USERNAME=${USERNAME:-defaultuser}
RUN echo "Hi, ${USERNAME}" > /tmp/hello.txt
CMD ["sleep", "100"]