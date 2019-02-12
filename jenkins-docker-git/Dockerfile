FROM openjdk:8

ADD target/jenkins-docker-git.jar jenkins-docker-git.jar

EXPOSE 9090

ENTRYPOINT ["java","-jar","jenkins-docker-git.jar"]

