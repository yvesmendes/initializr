FROM ubuntu:focal-20211006

ADD setup.sh /setup.sh
ADD get-jdk-url.sh /get-jdk-url.sh
RUN ./setup.sh java11

ENV JAVA_HOME /opt/openjdk
ENV PATH $JAVA_HOME/bin:$PATH