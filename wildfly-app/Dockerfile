FROM jboss/base-jdk:11
ADD wildfly-23.0.0.Final.tar.gz /wildfly-ws
ENV JBOSS_HOME /wildfly-ws/wildfly-23.0.0.Final/ 
COPY jboss-as-helloworld.war /wildfly-ws/wildfly-23.0.0.Final/standalone/deployments
USER jboss
EXPOSE 8080
CMD [ "/wildfly-ws/wildfly-23.0.0.Final/bin/standalone.sh", "-b", "0.0.0.0" ]



