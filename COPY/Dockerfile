FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf index.html
COPY index.html /usr/share/nginx/html
CMD ["nginx","-g","deamon off;"]
