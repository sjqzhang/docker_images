
prepare base.tar.gz from centos vm 

tar czvf base.tar.gz /home/product/dubbo_framework/ /home/product/java_config_center  /home/product/arch/java/base_component /usr/java/jdk1.7.0_79

wget -O CentOS-Base.repo http://mirrors.aliyun.com/repo/Centos-7.repo


Failed to get D-Bus connection: Operation not permitted

docker run --privileged -ti --name test1  centos /usr/sbin/init
