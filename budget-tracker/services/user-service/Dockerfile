FROM openjdk:8-jre-alpine
COPY target/*.jar /apps/user-service.jar
EXPOSE 8085
ENTRYPOINT [ \
    "java",\
    "-jar",\
    "/apps/user-service.jar"\
]
