FROM centos:7

RUN yum -y install httpd

ADD webserver.tar.gz /var/www/html

CMD ["-D", "FOREGROUND"]

ENTRYPOINT [ "/usr/sbin/httpd" ]

EXPOSE 80

#build image
# docker build . -t challenge:2
# docker run -p 8080:80 chllenge:2
