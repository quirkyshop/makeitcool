FROM nginx

RUN ls
RUN pwd

COPY nginx.conf /etc/nginx/nginx.conf
COPY certs /etc/nginx/certs
COPY index.html /etc/nginx/index.html

RUN pwd

CMD ["nginx"]

EXPOSE 443

