FROM ubuntu:trusty

RUN apt-get install -y sudo
RUN useradd -m user && echo "user:password" | chpasswd && adduser user sudo
RUN echo 'user ALL=(ALL) NOPASSWD: ALL' >> /etc/sudoers
USER user
