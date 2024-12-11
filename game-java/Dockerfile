#game java
FROM openjdk:17-jdk-slim

WORKDIR /app

COPY game.java /app/game.java

RUN javac game.java

CMD ["java", "game"]
