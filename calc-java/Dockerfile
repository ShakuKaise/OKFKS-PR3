#calc java
FROM openjdk:17-jdk-slim

WORKDIR /app

COPY calc.java /app/calc.java

RUN javac calc.java

CMD ["java", "calc"]
