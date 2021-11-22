FROM ubi7/ubi:latest
MAINTAINER jjserranog
LABEL description="A basic UBI 7 image"
RUN yum install -y git ansible && \
yum clean all
RUN echo "Hello from Dockerfile" > /usr/share/httpd/noindex/index.html
EXPOSE 22
CMD ["/bin/bash"]
