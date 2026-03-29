#our image can be used  by other images as a base image put some conditions to execute the instructions in the dockerfile
FROM almalinux:latest
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILd COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]