# Como Estas Docker environment

This environment is used for the Como Estas On-Premise version. If you want to implement Como Estas in a Public Cloud environment use the following links:

- [Como Estas - AWS Serverless](https://github.com/quedate-en-casa/comoestas-serverless)
- [Como Estas - AWS Terraform](https://github.com/quedate-en-casa/comoestas-serverless)
- [Como Estas - AWS DynamoDB](https://github.com/quedate-en-casa/comoestas-serverless)

## Docker images

This project uses two docker images for **API** and **UI**.
The docker images are the following:

- quedateencasa/comoestas-api
- quedateencasa/comoestas-ui

These images are published in this **Docker Hub** organization:

https://hub.docker.com/orgs/quedateencasa/repositories

## Requirements

To deploy this version of the environment, you must install `Docker` and `docker-compose`.

## Getting started

Clone this repository and then execute the following command:

```shell
docker-compose up
```
Go to [http://localhost:8000](http://localhost:8000) to access the application.

## TODO

- [ ] Implement deployment for Kubernetes with Skaffold
- [ ] Add authentication and encryption on mongodb
- [ ] Letsencrypt support
- [ ] More documentation
- [ ] Contious integration
- [ ] Integration tests
