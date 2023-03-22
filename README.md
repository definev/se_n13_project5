# se_n13_project5: Tidmid - Note and AI Chatbot Software
Tidmid is a software project developed by team se_n13_project5. The project aims to provide users with a convenient note-taking application and a chatbot powered by AI technology.

## Project Structure
The project is structured into the following directories:

`mobile_app`: This directory contains the mobile application, which is built using Flutter. Users can take notes and interact with the AI chatbot through this application.

`server`: This directory contains the backend server, which is built using FastAPI. The server communicates with the mobile application and handles requests related to note-taking and chatbot interactions. The database used is MySQL.

`server/deployment`: This directory contains the necessary Docker configuration files for deploying the application.

## Getting Started
To run the application, you will need to have Docker installed on your machine. Once you have Docker installed, you can follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the server/deployment directory.
3. Create a folder named env inside server/deployment.
4. Create 3 files inside env: .app.env, .db.env, .openai.env. These files will contain the necessary environment variables for the application. Refer to the respective .env.sample files in the same directory for the required variables.
5. Run the following command to start the application: docker-compose up.
6. Once the application is running, you can access the mobile application at http://localhost:8080.

## Contributing
We welcome contributions to this project. If you are interested in contributing, please create a pull request and we will review it as soon as possible.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
