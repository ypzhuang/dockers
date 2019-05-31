FROM openresty/openresty:alpine

RUN  apk --no-cache add --update tzdata && \
     rm -rf /var/cache/apk/* 
ENV TZ=Asia/Shanghai

MAINTAINER John Zhuang <zhuangyinping@gmail.com>