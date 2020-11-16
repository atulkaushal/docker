FROM openjdk

RUN mkdir /usr/src/myapp

COPY ./TestDocker.java /usr/src/myapp

WORKDIR /usr/src/myapp

RUN javac TestDocker.java

CMD ["java", "TestDocker"]