FROM rockylinux:9
RUN yum -y install iproute vim iperf3 openssh-clients
RUN yum -y install dhcp-server
COPY dhcpd.conf /etc/dhcp/dhcpd.conf
