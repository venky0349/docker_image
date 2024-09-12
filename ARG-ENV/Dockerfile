FROM almalinux:8
ARG username
RUN adduser $username
USER $username
ARG PROJECT
ARG ENVIRONMENT
ARG USER
ENV PROJECT=${project}
ENV ENVIRONMENT=${dev}
ENV USER=${username}
CMD ["sleep","100"]




