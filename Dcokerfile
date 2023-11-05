FROM amazonlinux:2023
RUN ulimit -n 1024 && yum -y update && yum -y install \
    python311\
    python311-pip \
    python311-devel \
    zip \
    && yum clean all
RUN python3 -m  pip install pip==23.3.1
RUN pip install virtualenv==20.24.6
