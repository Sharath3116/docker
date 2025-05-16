FROM almalinux:8
RUN yum install nginx -yum
RUN rm -rf /user/share/nginx/html/index.html
COPY index.html /user/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]

