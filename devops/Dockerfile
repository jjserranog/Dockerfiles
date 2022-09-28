FROM ubi8/ubi:latest
MAINTAINER jjserranog@gmail.com
LABEL description="A basic UBI 7 image with git "
RUN yum install -y git && \
yum clean all
RUN echo "Hello from Dockerfile" > /usr/share/httpd/noindex/index.html
EXPOSE 22
CMD ["/bin/bash"]
