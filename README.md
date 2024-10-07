# Hatio_Home_Challenge
## Step 1: Download the Project.
   + Downloaad the zip files.
   + Extract the files.
## Step 2: Set Up the Backend
  1. Navigate to the backend directory :  
     ```
     cd Todo_App
     ```
  3. Open the ```src/main/resources/application.properties``` file in a text editor.
  4. Configure your MySql database connection by updating the following properties:
     ```
         spring.datasource.driver-class-name = com.mysql.cj.jdbc.Driver
         spring.datasource.username = root
         spring.datasource.password = sql123
     ```
     Replace root and sql123 with your actual MySql database credentials.
  5. Build the Spring Boot application by running :
     ```
     ./mvnw clean install
     ```
## Step 3: Set Up the Frontend
1. Navigate to the frontend directory:
   ```
   cd Todo-Frontend
   ```
3. Install the necessary dependencies by running:
   ```
   npm install
    ```
# Running the Application
  ## Step 1: Start the Backend
  1. Ensure you are in the backend directory:
     ```
     cd Todo_App
     ```
2. Run the Spring Boot application with the following command:
   ```
    ./mvnw spring-boot:run   
    ```
The backend will run on http://localhost:8080.
  
## Step 2: Start the Frontend 
1. Ensure you are in the frontend directory:
 ```
   cd Todo-Frontend
   ```
2. Start the Vite development server by running:
  ```
  npm run dev
  ```
The frontend will be available at http://localhost:5173.

## note - 
+ you have to provide the basic login crediential for accessing the api's
  1. open console
  2. click on the url and you will get one popup box
  3. enter the credientials
  ```
  username : user
  password : user123
  ```


   
