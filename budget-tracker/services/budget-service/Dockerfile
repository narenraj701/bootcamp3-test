FROM openjdk:8-jre-alpine
COPY target/*.jar /apps/budget-service.jar
EXPOSE 8081
ENTRYPOINT [ \
    "java",\
    "-jar",\
    "/apps/budget-service.jar"\
]
