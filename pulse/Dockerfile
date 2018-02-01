FROM fedora:26
MAINTAINER Asaf Ohayon
RUN dnf upgrade -y && yum install -y firefox webkitgtk libgnome-keyring xulrunner mozjs17 libproxy-mozjs libproxy-gnome
COPY ps-pulse-linux-5.3r4.1-b1183-centos-rhel-64-bit-installer.rpm /
RUN rpm -ivh /ps-pulse-linux-5.3r4.1-b1183-centos-rhel-64-bit-installer.rpm
