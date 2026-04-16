ARG version
FROM almalinux:${version:-9}
ENV project="amazon-clone"
ARG services="catalogue"
ENV services=$services
RUN echo "Hi project is:${project} and service is ${services}"
CMD ["sleep","1000"]