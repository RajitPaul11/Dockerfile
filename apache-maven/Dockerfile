FROM centos:8
RUN yum install java-11-openjdk-devel -y
RUN yum install maven -y
CMD echo "export JAVA_HOME=/usr/lib/jvm/jre-openjdk" > /etc/profile.d/maven.sh
CMD echo "export M2_HOME=/opt/maven" >> /etc/profile.d/maven.sh
CMD echo "export MAVEN_HOME=/opt/maven" >> /etc/profile.d/maven.sh
CMD echo "PATH=${M2_HOME}/bin:${PATH}" >> /etc/profile.d/maven.sh
CMD chmod +x /etc/profile.d/maven.sh
CMD source /etc/profile.d/maven.sh
CMD /bin/bash

