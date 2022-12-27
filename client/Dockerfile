# Pull official base image
FROM node:13.12.0-alpine

# Set working directory
WORKDIR /app

# Copies package.json and package-lock.json to Docker environment
COPY package*.json ./

# Installs all node packages
RUN npm install --silent

# Copies everything over to Docker environment
COPY . .

# Exposes the server port
EXPOSE 3000

# Starts the server
CMD ["npm", "start"]
