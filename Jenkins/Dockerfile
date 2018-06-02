FROM jenkins/jenkins:lts

MAINTAINER christian altamirano

USER root
RUN mkdir /var/log/jenkins
RUN chown -R jenkins:jenkins /var/log/jenkins
USER jenkins

VOLUME ["jenkins_home", "/var/jenkins_home"]

EXPOSE 8080