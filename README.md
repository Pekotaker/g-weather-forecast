1. To run locally:

   1. Clone the repository
   2. Make sure you have Docker installed
   3. Fill in the environment variables in the .env file in /backend folder, as shown in the .env.template file
   4. Run the following command in the terminal:
      ```bash
      docker-compose up --build
      ```
   5. The application will be running on http://localhost:8000
   6. Subsequent runs can be done with the following command:
      ```bash
      docker-compose up
      ```

2. Online:
   1. The backend application is deployed on Render and can be accessed at https://g-weather-forecast-v0-1.onrender.com
