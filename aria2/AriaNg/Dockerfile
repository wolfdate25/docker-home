FROM nginx:stable-alpine

WORKDIR /app
RUN curl -sfL https://github.com/mayswind/AriaNg/releases/download/1.2.5/AriaNg-1.2.5-AllInOne.zip -O
ADD https://github.com/mayswind/AriaNg/releases/download/1.2.5/AriaNg-1.2.5-AllInOne.zip /usr/share/nginx/html
RUN unzip AriaNg-1.2.5-AllInOne.zip
RUN cp index.html /usr/share/nginx/html/
COPY nginx.conf /etc/nginx/conf.d/nginx.conf
