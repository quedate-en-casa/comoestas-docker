# Como Estas Docker environment

This environment is used for the Como Estas On Premise versión. If you want implement Como Estas in a Public Cloud environment this links can be useful for you:

- [Como Estas - AWS Serverless](https://github.com/quedate-en-casa/comoestas-serverless)
- [Como Estas - AWS Terraform](https://github.com/quedate-en-casa/comoestas-serverless)
- [Como Estas - AWS DynamoDB](https://github.com/quedate-en-casa/comoestas-serverless)

## Docker images

This project use two docker images for **API** an **UI**.
The following docker images are:

- quedateencasa/comoestas-api
- quedateencasa/comoestas-ui

This images are published in this **Docker Hub** organization:

https://hub.docker.com/orgs/quedateencasa/repositories


## Requirements

To deploy this versión of the environment, you must install `Docker` and `docker-compose`.

## Getting started

## TODO

- [ ] Implement deployment for Kubernetes with Skaffold
- [ ] Add authentication and encryption on mongodb
- [ ] Letsencrypt support
- [ ] More documentation
- [ ] Contious integration
- [ ] Integration tests