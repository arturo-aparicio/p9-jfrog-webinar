ARG REGISTRY=p9demo-artifactory.jfrog.team

FROM ${REGISTRY}/docker-framework:latest

MAINTAINER Stanley Fong stanleyf@jfrog.com

ADD war/*.war /home/exec/tomcat/webapps/ROOT.war

CMD /bin/bash -c cd /home/exec; /home/exec/tomcat/bin/catalina.sh run
