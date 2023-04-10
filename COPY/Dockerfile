FROM almalinux
RUN yum install nginx-y
RUN yum install epel release -y
copy /usr/share/nginx/html
CMD ["nginx" "-g" "daemon off;"]