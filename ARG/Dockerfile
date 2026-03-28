ARG version
FROM almalinux:${version:-8}
RUN echo "Hello World" > /index.html
ARG version=1.0.0 \
    description="This is a sample image for learning dockerfile instructions" \
    maintainer="RAMANA REDDY" \
    course="DevOps with docker" \
    author="RAMANA REDDY" \
    duration="2hrs"
RUN echo "This is version ${version} of the image ${description} created by ${author} for the course ${course} with duration ${duration}" > /index.html
CMD [ "sleep", "100" ]



