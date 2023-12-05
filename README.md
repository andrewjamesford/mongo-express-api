# An express API you can connect to MongoDB

## Getting Started
1. Clone the repo to your local machine
2. Install the node modules for the `server`
3. Run the Docker command [below](#docker) in the terminal to start the mongo container
4. Run `npm run start:dev` in the terminal to start the server

### Prerequisites
- Docker
- NodeJS

### Docker
```bash
docker run --name mongo-express-api \
  -p 27017:27017 \
  -v mongo-express-api_data_container:/data/db \
  -d \
  mongo
```