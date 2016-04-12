FROM centos:7

RUN yum update -y
RUN yum install -y \
      git \
      gcc \
      openssl-devel \
      python-setuptools \
      python-devel && \
    easy_install pip && \
    pip install \
      six \
      httplib2
RUN pip install "git+https://github.com/ansible/ansible.git"
