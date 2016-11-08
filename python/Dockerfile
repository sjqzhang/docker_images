FROM alphine-base


ADD pip.conf /etc/pip.conf
RUN echo "https://mirror.tuna.tsinghua.edu.cn/alpine/v3.4/main/" > /etc/apk/repositories && \
apk update && \
apk add gcc libffi-dev musl-dev openssl-dev  && \
apk add python py-paramiko py-gunicorn py-pip python-dev py-requests py-redis py-mysqldb py-lxml py-yaml py-curl && \
pip install falcon requests gevent pymysql fabric pexpect redis kazoo memcache_wrapper DBUtils jinja2  && \

#### common packages ####
#apk add  python py-setuptools 	py-libvirt py-pip python-dev gcc  libusb py-pip python-dev gcc linux-headers gcc git libffi-dev musl-dev openssl-dev perl py-pip python python-dev sshpass  && \
#pip install libvirt-python
#pip install requests dnspython IPy XlsxWriter  scapy pexpect paramiko fabric ansible gevent netmiko docker-py kazoo falcon peewee gunicorn pyzabbix redis kazoo pika kafka-python autojenkins ldap3 boto psutil ansible elasticsearch  simplejson requests python-dateutil lxml

#### end common packages ####

apk del gcc libffi-dev musl-dev openssl-dev 
ENTRYPOINT ["/init"]
CMD []
