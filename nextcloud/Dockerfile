FROM nextcloud:fpm-alpine

RUN addgroup -g 2000 tank && adduser www-data tank

RUN apk --no-cache add imagemagick imagemagick-svg bzip2-dev

RUN docker-php-ext-install bz2
