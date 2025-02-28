FROM almalinux:9
ENV course="Devops with AWS" \
    trainer="sivakumar reddy" \
    duration="120HRS"
# here username is key , some_user is default value
ARG ${username:-some_user}    
RUN echo "Hello ${username}" > /tmp/devops.txt
CMD ["sleep", "100"]        