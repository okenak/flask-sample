FROM amazonlinux:2

RUN yum -y update && \
    yum -y install \
        wget \
        which \
        vim \
        less s && \
    amazon-linux-extras install python3.8 && \
    yum clean all

EXPOSE 5000

WORKDIR /workspace