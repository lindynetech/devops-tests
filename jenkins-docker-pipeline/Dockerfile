# use a node base image
FROM alpine:latest

# set maintainer
LABEL maintainer "lindynetech@gmail.com"

RUN apk add -u nginx && mkdir -p /run/nginx

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]



