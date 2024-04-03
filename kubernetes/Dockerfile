FROM openjdk:8-jdk
WORKDIR /jmeter
COPY default-script.jmx /jmeter/
COPY jmeter /jmeter/app
ENV JMETER_HOME /jmeter/app
ENV PATH "$JMETER_HOME/bin:${PATH}"