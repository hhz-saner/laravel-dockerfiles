FROM nginx:alpine

RUN set -x ; \
    addgroup -g 82 -S www-data ; \
    adduser -u 82 -D -S -G www-data www-data ;

CMD ["nginx", "-g", "daemon off;"]

EXPOSE 80 443
