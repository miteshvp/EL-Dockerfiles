FROM quay.io/openshiftio/rhel-base-pcp:latest

RUN yum -y update && \
    yum -y install https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm && \
    yum -y install python-pip git && \
    pip install --upgrade pip && \
    yum clean all
