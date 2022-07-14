# Welcome to the Anythink Market repo

To start the app use Docker. 
Install Docker from - https://docs.docker.com/desktop/

It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Once you clone project from repository to your local, open that project in VS Code.
2. You can verify docker version by commands docker -v and docker-compose -v
3. Open terminal and enter command in root directory as docker-compose up , It will take some time to download all dependencies and instance can be seen running in Docker application
4. If Docker is working correctly, the backend should be running and able to connect to your local database. You can test this working properly or not by browsing http://localhost:3000/api/ping
5. By clicking on frontend instance in Docker Application there is option "Open in Browser" , once you click you will get user interface.
6. Try creating user by clicking on Signup and you done
