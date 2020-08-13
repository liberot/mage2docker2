FROM debian 

RUN apt-get update                      && \
  apt-get -y install apache2 vim        && \
  a2enmod rewrite                       && \
  a2enmod headers                       && \
  apt-get -y install       \
    php7.3                 \
    php7.3-curl            \
    php7.3-intl            \
    php7.3-gd              \
    php7.3-dom             \
    php7.3-iconv           \
    php7.3-xsl             \
    php7.3-mbstring        \
    php7.3-ctype           \
    php7.3-zip             \
    php7.3-pdo             \
    php7.3-xml             \
    php7.3-bz2             \
    php7.3-calendar        \
    php7.3-exif            \
    php7.3-fileinfo        \
    php7.3-json            \
    php7.3-mysqli          \
    php7.3-mysql           \
    php7.3-posix           \
    php7.3-tokenizer       \
    php7.3-xmlwriter       \
    php7.3-xmlreader       \
    php7.3-phar            \
    php7.3-soap            \
    php7.3-mysql           \
    php7.3-fpm             \
    php7.3-bcmath          \
    libapache2-mod-php7.3

WORKDIR /var/www/html
CMD sh ./setup.sh

CMD apachectl -DFOREGROUND

