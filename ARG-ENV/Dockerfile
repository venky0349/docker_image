ARG version
FROM almalinux:${version}
ARG username
RUN adduser $username
USER $username
ARG PROJECT
ARG ENVIRONMENT
ENV PROJECT=${PROJECT}
ENV ENVIRONMENT=${ENVIRONMENT}
CMD ["sleep","100"]




