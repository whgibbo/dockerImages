# Pull base image.
FROM ubuntu:16.04

# Install Java.
RUN \
  apt-get update && \
  apt-get install -y openjdk-8-jre-headless && \
  rm -rf /var/lib/apt/lists/*
  
CMD ["java", "-version"]
