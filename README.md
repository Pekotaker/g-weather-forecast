# To run locally:

1.  Clone the repository
2.  Make sure you have Docker installed

## Backend

3.  Fill in the environment variables in the .env file in /backend folder, as shown in the .env.template file
4.  Run the following command in the terminal to run the backend:
    ```bash
    docker-compose up --build
    ```
5.  The application's backend will be running on http://localhost:8000
6.  Subsequent runs can be done with the following command:

    ```bash
    docker-compose up
    ```

## Frontend

7. cd into the frontend folder using the following command on a different terminal:

   ```bash
   cd frontend
   ```

8. Change the `SERVER_BASE_URL` in src/config.js to `http://localhost:8000`

9. Run the following command in the terminal to run the frontend:

   ```bash
   npm install
   npm start
   ```

10. The application's frontend will be running on http://localhost:3000

11. Subsequent runs can be done with the following command:

    ```bash
    npm start
    ```

# Online

1.  The backend application is deployed on Render and can be accessed at https://g-weather-forecast-v0-1.onrender.com
2.  The frontend application is deployed on Render and can be accessed at https://weather-forecast-fe-mqil.onrender.com/
