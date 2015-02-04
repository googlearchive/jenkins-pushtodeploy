FROM google/cloud-sdk
ADD swarm-client-1.9-jar-with-dependencies.jar $HOME/swarm-client.jar 
ADD get_labels.py $HOME/get_labels.py
CMD java -jar swarm-client.jar -master http://${JENKINS_SERVICE_HOST}:${JENKINS_SERVICE_PORT} -labels ${HOSTNAME} `python get_labels.py`
