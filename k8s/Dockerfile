# Base image
FROM amazonlinux:latest

# Update the package list and install Apache
RUN yum update -y && \
    yum install -y httpd
COPY index.html /usr/local/apache2/htdocs/
