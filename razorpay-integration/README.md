## Razorapay Integration App 

# Steps to run sample app:

- Edit the key inside index.ftl
- Add you api_key and api_secret in server.yml file:
---------------------------------
apiKey: your_api_key
secretKey: your_api_secret
---------------------------------
- Build 
mvn clean install -DskipTests
- Run 
java -jar target/razorpay-java-testapp-1.0-SNAPSHOT.jar server server.yml

Open http://localhost:8080/payment on browser and pay