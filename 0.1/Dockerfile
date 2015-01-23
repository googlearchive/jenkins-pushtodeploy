FROM jenkins
COPY /plugins.txt plugins.txt
USER root
RUN plugins.sh plugins.txt
USER jenkins
