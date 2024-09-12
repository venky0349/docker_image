FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD  https://github.com/venky0349/docker_image/blob/main/index.html  /usr/share/nginx/html/
EXPOSE 80/tcp
CMD ["nginx","-g","daemon off;"]
ENV TRAINER="VENKY"\
     DURATION="90DAYS"\
     PROJECT="ROBOSHOP"