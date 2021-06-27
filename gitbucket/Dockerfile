FROM openjdk:8-jre

LABEL maintainer="qwinsi <qwinsi@163.com>"
ADD ./gitbucket-4.35.3.war /opt/gitbucket.war

RUN ln -s /gitbucket /root/.gitbucket

VOLUME /gitbucket

# Port for web page and Port for SSH access to git repository (Optional)
EXPOSE 80 29418

CMD ["sh", "-c", "java -jar /opt/gitbucket.war --port=80"]
