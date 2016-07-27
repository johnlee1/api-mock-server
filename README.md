# api-mock-server

API-Mock is a nodejs module that generates a mock server from your api specification. <br />
The api specs must be in the API Blueprint format. <br />
Hercule is a command-line tool and library for transcluding API Blueprint. <br />
This repository is an example of a flask app connected with the mock server. <br />

# setup

Use docker-compose to set up the mock server with a volume mounted with the api specs. <br />
At the root of the mounted volume, have a file called mock-server.md. <br />