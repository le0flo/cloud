
FROM nginx:alpine
WORKDIR /srv

COPY ./index.html /srv/index.html
COPY ./style.css /srv/style.css
COPY ./assets /srv/assets

COPY nginx.conf /etc/nginx/nginx.conf

ENTRYPOINT ["nginx", "-c", "/etc/nginx/nginx.conf", "-g", "daemon off;"]
