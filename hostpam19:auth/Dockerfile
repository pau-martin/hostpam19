# ldapserver # ldapserver
FROM fedora:27
LABEL version="1.0"
LABEL author="Pau Martín"
LABEL subject="hostpam"
RUN dnf -y install vim procps iproute nmap util-linux-user finger passwd pam_mount nfs-utils nss-pam-ldapd
RUN mkdir /opt/docker
COPY * /opt/docker/
RUN chmod +x /opt/docker/startup.sh
WORKDIR /opt/docker

