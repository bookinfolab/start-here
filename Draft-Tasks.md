# Draft

## Tasks

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
### Monitoring
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
