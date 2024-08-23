FROM nginx 
RUN rm -f /usr/share/nginx/html/index.html
RUN rm -f /etc/nginx/default.d/nginx.conf
RUN rm -f /etc/nginx/conf.d/default.conf
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf
ADD static /usr/share/nginx/html

