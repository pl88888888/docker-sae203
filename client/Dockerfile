FROM openjdk:17
WORKDIR /app
COPY compile.list .
COPY ihm/ ./ihm/
COPY websocket/ ./websocket/
RUN javac @compile.list
CMD ["java", "websocket.Client"]

