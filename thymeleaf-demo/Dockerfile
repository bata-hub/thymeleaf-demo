# JDK 17 дээр суурилсан хөнгөн image ашиглах
FROM openjdk:17-jdk-slim

# Апп-ын ажлын хавтас үүсгэх
WORKDIR /app

# JAR файлыг container руу хуулах
COPY target/*.jar app.jar

# Апп-ын ашиглах портыг заах
EXPOSE 8080

# Апп-ыг ажиллуулах команд
ENTRYPOINT ["java", "-jar", "app.jar"]