FROM nginx:latest
COPY ./nginx.conf /etc/nginx/conf.d/

# RUN rm /etc/nginx/conf.d/default.conf

COPY /path/to/your/certificates /etc/letsencrypt/live/


WORKDIR /app

EXPOSE 80

CMD [ "nginx", "-g", "daemon off;" ]