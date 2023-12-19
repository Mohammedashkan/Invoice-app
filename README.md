# Invoice App

This is a sample Invoice app created using React, Java, and Python.

## Project Structure

invoice-app/
├── java/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   ├── com/
│   │   │   │   │   ├── example/
│   │   │   │   │   │   ├── invoice/
│   │   │   │   │   │   │   ├── controller/
│   │   │   │   │   │   │   │   ├── InvoiceController.java
│   │   │   │   │   │   │   ├── model/
│   │   │   │   │   │   │   │   ├── Invoice.java
│   │   │   │   │   │   │   ├── repository/
│   │   │   │   │   │   │   │   ├── InvoiceRepository.java
│   │   │   ├── resources/
│   │   │   │   ├── application.properties
│   ├── pom.xml
├── python/
│   ├── invoice.py
├── react/
│   ├── src/
│   │   ├── components/
│   │   │   ├── InvoiceList.js
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
├── README.md



## How to Run

1. Open the terminal in VS Code and navigate to the "java/invoice" folder.
2. Run the following command to start the Spring Boot app:


mvn spring-boot:run

3. Open a new terminal in VS Code and navigate to the "python" folder.
4. Run the following command to start the Python script:


python invoice.py

5. Open a new terminal in VS Code and navigate to the "react" folder.
6. Run the following command to start the React app:


npm start

7. Open your web browser and go to http://localhost:3000 to access the Invoice app.