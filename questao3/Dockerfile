FROM openjdk:8-jdk-alpine
COPY Principal.java Principal.java
COPY manifest.txt manifest.txt
RUN javac Principal.java
RUN jar -cfm Principal.jar manifest.txt Principal.class
CMD ["java" ,"-jar", "Principal.jar"]