FROM alphine-base

RUN echo "https://mirror.tuna.tsinghua.edu.cn/alpine/v3.4/main/" > /etc/apk/repositories && \
apk update && \
apk add php5 php5-mysql php5-json php5-iconv php5-common php5-fpm php5-gd php5-zlib php5-pdo php5-ldap

#### all php5 package ######

#php5-opcache php5-wddx php5-sysvshm php5-xsl php5-xmlreader php5-sysvsem php5-zlib php5-sysvmsg php5-mssql php5-xmlrpc php5-sqlite3 php5-pdo_dblib php5-xml php5-zip php5-pdo_sqlite php5-soap php5-pcntl php5-pdo php5-shmop php5-snmp php5-openssl php5-posix php5-sockets php5-pdo_odbc php5-odbc php5-phar php5-pspell php5-pdo_mysql php5-pgsql php5-pdo_pgsql php5-enchant php5-dba php5-intl php5-imap php5-gmp php5-mcrypt php5-ftp php5-ldap php5-mysql php5-gd php5-mysqli php5-gettext php5-json php5-curl php5-exif php5-iconv php5-dom php5-cgi php5-common php5-bz2 php5-bcmath php5-phpdbg php5-fpm php5-doc php5-calendar php5-cli php5-ctype php5-pear php5-embed php5-apache2 php5-dbg php5-dev php5-pear php5-memcache php5-apcu php5-xcache php5-pear php5-phalcon php5-pear php5-pear php5-pear php5-pear php5-pear php5-pear php5-pear php5-pear php5-mailparse php5-phpmailer


#### end php5 package ######


ENTRYPOINT ["/init"]
CMD []
