FROM almalinux
RUN dnf install nginx -y

RUN rm -rf /usr/share/nginx/html/index.html
COPY hello  /usr/share/nginx/html/index.html

CMD ["nginx","-g","daemon off;"]
