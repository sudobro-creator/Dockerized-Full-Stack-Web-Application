FROM nginx:latest
COPY ./nginx.conf /etc/nginx/default.conf

RUN rm /etc/nginx/conf.d/default.conf

CMD [ "nginx", "-g", "daemon off;" ]