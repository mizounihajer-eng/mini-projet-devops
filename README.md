# Mini Projet DevOps - CI/CD et Docker

Application Node.js simple conteneurisée avec Docker
et déployée via un pipeline CI/CD GitHub Actions.

## Technologies
- Node.js
- Docker
- GitHub Actions

## Lancer l'application
node app.js

## Docker
docker build -t monnom/mini-projet-devops:v1 .
docker run -p 3000:3000 monnom/mini-projet-devops:v1