FROM zabbix/zabbix-server-pgsql:alpine-3.2-latest
LABEL maintainer="behnam.hasanbeygi@gmail.com"

RUN apk update && apk add sudo nmap && echo "zabbix ALL=(ALL) NOPASSWD: ALL" > /etc/sudoers && chmod 4755 /bin/ping