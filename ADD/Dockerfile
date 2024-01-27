FROM almalinux:8
RUN yum install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
ADD listing-master /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]