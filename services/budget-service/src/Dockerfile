FROM nginx

VOLUME /usr/share/nginx/html/budget

VOLUME /etc/nginx

COPY index.html /usr/share/nginx/html/budget/index.html

COPY /config/default.conf /etc/nginx/conf.d

EXPOSE 8000
