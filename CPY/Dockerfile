FROM almalinux:9 
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.hmtl 
COPY index.html  /usr/share/nginx/html/index.hmtl
CMD ["nginx","-g","daemon off;"]
