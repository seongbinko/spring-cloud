FROM openjdk:17-ea-11-jdk-slim
VOLUME /tmp
# container의 key 파일을 도커 컨테이너의 root폴더에 복사
COPY apiEncryptionKey.jks apiEncryptionKey.jks
COPY build/libs/config-service-1.0.jar ConfigServer.jar
ENTRYPOINT ["java", "-jar", "ConfigServer.jar"]