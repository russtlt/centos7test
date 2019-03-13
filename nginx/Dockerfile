FROM centos

MAINTAINER Ruslan Diadin <russtlt@gmail.com>

RUN 	yum install -y epel-release && \
	yum update -y && \
	yum install -y nginx && \
	mkdir /var/www  > /dev/null

WORKDIR /var/www

#CMD ["nginx"]
ENTRYPOINT ["/usr/sbin/nginx","-g","daemon off;"]
EXPOSE 80

