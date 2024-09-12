FROM almalinux:8
RUN adduser venky 
USER venky
WORKDIR /tmp
RUN echo "if we use the RUN to create the dir  /tmp  and use that directory it won't ctreate and the created files will goto the default directory not /tmp dir  " > restfile.txt
CMD ["sleep", "100"]