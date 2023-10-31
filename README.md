# start-here

---
## BookInfo

---
## Tasks

### Get code
Setup Local/Cloud Environment
- [ ] ...
Run `ratings` service in local/cloud environment
- [ ] Create a new repository based on the [ratings](https://github.com/bookinfolab/ratings) template repository, do not fork it.
- [ ] Clone your `ratings` repository on your local environment
- [ ] Install required software in order to start up the app like [NodeJS](https://nodejs.org/)
- [ ] Run the app
- [ ] Call to mock endpoint using any HTTP CLI tool
Create `Postman` tests
- [ ] Call the mock endpoint using Postman HTTP client, it returns default hard-coded data.
- [ ] Create a Postman collection and environment that calls to the mock endpoint.
- [ ] Add an assertions to the Postman request to validate status code and data.
- [ ] Install `Newman` CLI that allows to run `Postman` collections as tests
- [ ] **(Optional)** Integrate the source code with any linter tool.
Build and pushing `ratings` container image using `docker` CLI
- [ ] Create a `Dockerfile` for `ratings` app.
- [ ] Run the `ratings` container
- [ ] Run Postman tests using newman
- [ ] Build and push your docker image to any registry.
Support `mongodb` as DB engine to store ratings information
- [ ] Create a new repository based on the `mongodb` template repository, do not fork it.
- [ ] Clone the `mongodb` repository on your local environment
- [ ] Install any mongo GUI tools in order to connect to the mongodb instance 
- [ ] Import `ratings_data.json` data in a collection using your installed mongo GUI.
- [ ] Import `ratings_data.json` data in a collection using mongo CLI.
- [ ] Document your local setup and importing data from GUI and CLI.
- [ ] Create a bash script that imports `ratings_data.json` data, make sure it's working and commit the script.
Build and pushing `mongodb` container image using `buildah` CLI
- [ ] Create a `Dockerfile` that contains the collection and data of `ratings_data.json`.
- [ ] Build the `Docker Image` called `mongodb`.
- [ ] Make sure your `Docker Image` is working using your mongo GUI or CLI
- [ ] Document your docker commands and push your changes
Integrate `ratings` with `mongodb`
- [ ] Creating a network using docker commands.
- [ ] Create a volume for mongodb data
- [ ] Run `mongodb` container connected to the nertwork previously created and mounting to the volume.
- [ ] Run `ratings` container connected to the nertwork, expousing port and define environment variables to interact with mongodb.
- [ ] Run postman tests using newman, perform changes if needed.
- [ ] Documment commands
Create Docker Compose that integrates `ratings` with `mongodb` 
- [ ] Create a new repository based on the [compose](https://github.com/bookinfolab/compose) template repository, do not fork it.
- [ ] Clone `compose` repository on your local environment
- [ ] Create a compose file using `v2.*` that defines the services `mongo` and `ratings`
- [ ] Get up containers defined within the compose file
- [ ] Run postman tests for `raitings` using newman.
- [ ] Document commands
Migrate to `mySql` from `mongodb` and support both DB engines
- [ ] Create a new repository based on the [mysql](https://github.com/bookinfolab/mysql) template repository, do not fork it.
- [ ] Install `mysql` on your local with any GUI
- [ ] Create a DB and insert data
- [ ] Create a SQL script to generate the DB with default data, same data than mongodb
- [ ] Run SQL from CLI
Build and pushing `mysql` container image using `kaniko` CLI
- [ ] ...
Include `mysql` on compose file to integrating with `rating`
- [ ] ...
Deploy on PWD
- [ ] ...
Add a linter to the `ratings` source code
- [ ] ...
Create a pipeline for `ratings`
- [ ] Add a linter
- [ ] Build and push
Create a pipeline for `mongodb`
- [ ] Add a linter
- [ ] Build and push
Create a pipeline for `mysql`
- [ ] Add a linter
- [ ] Build and push
Run tests as part of CI
- [ ] Run tests
- [ ] Report
Generate compose graph
- [ ] 
Refactor Compose

### Static analisis code
### Run Tests
### Build Docker Images
### Dockerfile Linter
### Include tests / Unit/Integration/End
### Push Docker Images
### Docker Image Security Scan
### Docker testing
### CI
### Docker Compose DEV/QA
### Play with Docker
### .env
### Secrets
### Logs
### nginx
### Authentication
### Docker Swarm
### Terraform with Docker Provider
### Terraform with AWS Provider
### Terragrount
### Terratest
### Kubernetes
### Helm
### lstio
