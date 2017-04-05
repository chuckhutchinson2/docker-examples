FROM registry.access.redhat.com/rhel7/rhel-atomic:latest

ADD dist/jdk-8u121-linux-x64.tar.gz /opt/java/

RUN ls -al /opt/java

ENV JAVA_HOME /opt/java/jdk1.8.0_121
ENV PATH $PATH:$JAVA_HOME/bin

