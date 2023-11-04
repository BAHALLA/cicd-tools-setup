# This repository contains samples to setup cicd tools

## Jenkins

This example provides a setup of jenkins controller and jenkins agent using docker compose with ssh authentification.

To run this example go to jenkins folder `cd jenkins` and run the following command
```
docker compose up -d
```
then you can access jenkins in http://localhost:8080
for more information about how to setup this configuration [check out this link](https://www.cloudbees.com/blog/how-to-install-and-run-jenkins-with-docker-compose)
