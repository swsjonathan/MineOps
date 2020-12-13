FROM jenkins/jenkins:lts
USER root
RUN echo "root:lawcoinrank" | chpasswd

COPY contrasena /var/jenkins_home

RUN apt update
RUN apt install file -y