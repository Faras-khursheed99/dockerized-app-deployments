# SabziCart API - Docker Deployment

A Node.js REST API containerized using Docker and deployed on AWS EC2.

## Technologies
- Node.js
- Express.js
- Docker
- Docker Hub
- AWS EC2
- Nginx
- Let's Encrypt SSL

## API Endpoints
- GET / - API welcome message
- GET /api/health - Health check
- GET /api/prices - Product prices

## Docker Build
docker build -t sabzicart-api:1.0 .

## Run Container
docker run -d --name sabzicart-api -p 3000:3000 sabzicart-api:1.0

## Live API
https://faras-nodeapi.falconsoftwares.com/api/health
