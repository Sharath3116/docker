FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-76s/notes/refs/heads/master/session-02.txt /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]

