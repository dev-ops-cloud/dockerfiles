ARG version
FROM almalinux:${version:-9}
ENV course="Devops with AWS" \
    trainer="sivakumar reddy" \
    duration="120HRS"
# here username is key , some_user is default value
ARG USERNAME=sivakumar    
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]        