FROM java:8

EXPOSE 8080

ADD target/docker-kube-demo.jar docker-kube-demo.jar

ENTRYPOINT ["java", "-jar","docker-kube-demo.jar"]