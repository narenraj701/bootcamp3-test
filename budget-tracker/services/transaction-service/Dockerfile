FROM openjdk:8-jre-alpine
COPY target/*.jar /apps/transaction-service.jar
EXPOSE 8082
ENTRYPOINT [ \
    "java",\
    "-jar",\
    "/apps/transaction-service.jar"\
]
