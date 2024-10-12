FROM cytopia/ansible:latest

RUN apk update
RUN apk add openssh sshpass net-tools

COPY ./inventory.ini /data
COPY ./pinghost.yml /dest

