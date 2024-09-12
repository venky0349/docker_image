FROM almalinux:8
RUN yum install nginx -y
EXPOSE 80/tcp
CMD ["nginx","-g","daemon off;"]
ENV TRAINER="VENKY"\
     DURATION="90DAYS"\
     PROJECT="ROBOSHOP"