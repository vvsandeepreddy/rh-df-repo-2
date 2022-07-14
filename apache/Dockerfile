FROM komljen/ubuntu
MAINTAINER Alen Komljen <alen.komljen@live.com>

RUN \
  apt-get update && \
  apt-get -y install \
          apache2 && \
  rm /var/www/html/index.html && \
  rm -rf /var/lib/apt/lists/*

FROM komljen/ubuntu:123 AS raju


FROM komljen/ubuntu:456 AS Akthar
