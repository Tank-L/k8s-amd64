FROM nginx:stable-alpine
COPY nginx.conf /etc/nginx/nginx.conf
ADD dist.tar.gz /usr/share/nginx/html/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
