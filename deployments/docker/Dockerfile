#
FROM maven
COPY . /app
WORKDIR /app
RUN mvn install
EXPOSE 8080
CMD ["java","-jar","target/food_delivery-0.1.jar"]
