FROM registry.access.redhat.com/rhel7/rhel-atomic:latest

ADD dist/jdk-8u121-linux-x64.tar.gz /opt/java/

RUN ls -al /opt/java

WORKDIR /opt/java/jdk1.8.0_121/
RUN alternatives --install /usr/bin/java java /opt/java/jdk1.8.0_121/bin/java 2

ENV JAVA_HOME /opt/java/jdk1.8.0_121

# not needed since we used alternatives
# ENV PATH $PATH:$JAVA_HOME/bin

