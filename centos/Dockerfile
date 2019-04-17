FROM centos
COPY CentOS-Base.repo /etc/yum.repos.d/CentOS-Base.repo
#ADD base.tar.gz /
#ADD publish_product.tar.gz /
#COPY config_center.properties  /home/product/java_config_center/config_center.properties
#ENV PATH=$PATH:/usr/java/jdk1.7.0_79/bin
#ENV JAVA_HOME=/usr/java/jdk1.7.0_79
RUN yum install -y net-tools which openssh-server iproute && systemctl enable sshd 

RUN mkdir /root/.ssh && chmod 700 /root/.ssh && echo "" >> /root/.ssh/authorized_keys
ENTRYPOINT ["/usr/sbin/init"]
CMD []
