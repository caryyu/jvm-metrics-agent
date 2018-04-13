FROM tomcat:7.0.72-jre8

ADD https://github.com/jmxtrans/jmxtrans-agent/releases/download/jmxtrans-agent-1.2.6/jmxtrans-agent-1.2.6.jar /
ADD ./jmxtrans-agent.xml /

CMD ["catalina.sh", "run"]