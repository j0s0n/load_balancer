FROM nginx
RUN rm /etc/nginx/conf.d/default.conf /usr/share/nginx/html/index.html
COPY site3.conf /etc/nginx/conf.d/default.conf
COPY index.html /usr/share/nginx/html/index.html
