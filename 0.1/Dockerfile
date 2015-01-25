FROM jenkins
ADD plugins.txt /usr/share/jenkins/
ADD kubernetes.hpi $JENKINS_HOME/plugins/
USER root
RUN plugins.sh /usr/share/jenkins/plugins.txt
