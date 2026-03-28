FROM almalinux:9
RUN dnf install nginx -y
#required root access to install nginx and start the nginx service.
RUN useradd roboshop
USER roboshop
CMD ["sleep", "100"]