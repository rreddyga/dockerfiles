FROM redhat/ubi9 
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]
LABEL maintainer="RAMANA REDDY" \
      version="1.0" \
      description="This is a sample Dockerfile for nginx on UBI9" \
      COURSE="Docker for Beginners" \
      AUTHOR="RAMANA REDDY" \   
      DURATION="2 hours" \
      TOPICS="Dockerfile, nginx, UBI9"
# Setting environment variables for MongoDB connection details accessible in the container
ENV MONGO_URL="mongodb-dev.sanathananelaform.online" \
    MONGO_USERNAME="admin" \
    MONGO_PASSWORD="admin123" \