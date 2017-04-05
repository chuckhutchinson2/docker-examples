FROM rhel7-jdk:latest

WORKDIR /opt/springboot/

ADD dist/ /opt/springboot/

RUN chmod ugo+x springboot.sh

CMD /opt/springboot/springboot.sh



