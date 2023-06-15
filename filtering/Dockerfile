FROM openjdk
COPY ./JavaServiceFiltering-all-1.0-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
#/**
# * Команды для терминала:
# * ./gradlew clean - очищаем директорию build
# * ./gradlew build - сборка приложения
# * ./gradlew run - запуск приложения
# * ./gradlew jar - упаковка приложения в jar
# *
# * Docker Desktop должен быть запущен для выполнения следующих команд:
# * docker image build -t java-docker-application-jar:latest C:\Users\yvnenak2\IdeaProjects\JavaApplicationInDocker\ - build образа для Docker
# * docker run java-docker-application-jar:latest - запуск приложения в Docker
# *
# * docker-compose up - поднять сервисы через docker-compose
# */
