# config-repo
configs for all projects


./gradlew clean build
docker build -t config-service .
docker run -d -p 8888:8888 --name config-service config-service
