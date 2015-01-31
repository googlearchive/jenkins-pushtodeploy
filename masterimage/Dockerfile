FROM jenkins
ADD plugins.txt /usr/share/jenkins/
ADD kubernetes-workflow-steps.hpi $JENKINS_HOME/plugins/
USER root
RUN plugins.sh /usr/share/jenkins/plugins.txt

