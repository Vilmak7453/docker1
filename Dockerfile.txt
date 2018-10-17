FROM nginx:alpine

COPY ./harkka2_3.html /usr/share/nginx/html/index.html

EXPOSE 80

#CMD nginx