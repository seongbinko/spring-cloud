FROM openjdk:17-ea-11-jdk-slim
VOLUME /tmp
# container의 key 파일을 도커 컨테이너의 root폴더에 복사
COPY build/libs/discoveryservice-1.0.jar DiscoveryService.jar
ENTRYPOINT ["java", "-jar", "DiscoveryService.jar"]