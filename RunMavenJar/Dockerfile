FROM java:8

COPY target /code/target

WORKDIR /code

# and if necessary
# EXPOSE 9000

ENTRYPOINT ["java","-jar","/code/target/app.jar"]
