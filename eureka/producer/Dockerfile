FROM fabric8/java-centos-openjdk8-jdk:1.3.1

RUN mkdir /springcloud
COPY target/learning-springcloud-eureka-producer-*.jar /springcloud/learing-springcloud-eureka-producer.jar

EXPOSE 1111
CMD ["java","-jar","-Djava.security.egd=file:/dev/./urandom","/springcloud/learing-springcloud-eureka-producer.jar"]
