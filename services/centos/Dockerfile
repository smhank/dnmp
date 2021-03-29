
FROM centos
ENV TZ "Asia/Shanghai"

RUN yum install -y lrzsz curl wget tar zip unzip vim-enhanced passwd sudo && \
    yum install -y nc net-tools  && \
    yum clean all


WORKDIR /var/www
