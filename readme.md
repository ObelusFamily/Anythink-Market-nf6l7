# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## Set up
### Install Docker
- Install Docker from here https://docs.docker.com/get-docker/
- Verify docker install by running `docker -v` and `docker-compose -v`
Then, run `docker-compose up` from the project root directory to load the front/back end
- If Docker is working correctly, the backend should be running and able to connect to your local database here http://localhost:3000/api/ping     

### Next steps
- check the frontend and make sure it’s connected to the backend.
If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register
### Note 
- Make sure that you run all scripts on one of the containers created by `docker-compose up`.  You can also use `docker exec` to run commands on a running container.