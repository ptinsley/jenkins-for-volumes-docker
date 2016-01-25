# jenkins-for-volumes-docker

Jenkins Docker image to use easily with volume mounts

If JENKINS_HOME is owned by root, then change it to jenkins user before starting Jenkins.

Otherwise start normally.

Unless otherwise set with -e, JENKINS_HOME will be /var/jenkins_home.
