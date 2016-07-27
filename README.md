# api-mock-server

API-Mock is a node.js npm module that generates a mock server from your api specification.<br />
Document your api in the API Blueprint format, and API-Mock mocks your routes and sends the responses defined in the api spec.<br />
Hercule is a command-line tool and library for transcluding API Blueprint.<br />
Use docker-compose to set up the mock server with a volume mounted with the api specs.<br />
At the root of the mounted volume, have a file called mock-server.md.<br />
