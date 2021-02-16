FROM amazonlinux:2

RUN yum update -y && \
    yum install -y httpd

EXPOSE 80

CMD ["httpd", "-DFOREGROUND"]

