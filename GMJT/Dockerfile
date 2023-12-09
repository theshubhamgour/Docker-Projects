FROM ubuntu
LABEL maintainer="theshubhamgour"

# Update the package list and install required packages
RUN apt-get update -y && apt-get upgrade -y && \
    apt-get install -y git maven && \
    apt-get install -y openjdk-17-jdk openjdk-17-jre && \
    apt-get install -y tomcat9

# Optionally, you can expose ports if needed
# EXPOSE 8080

# This CMD command will be executed when the container starts
CMD ["bash"]

