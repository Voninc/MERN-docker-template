# Use a specific version of the Node.js image
FROM node:20.6.0

WORKDIR /app
COPY package.json .
COPY package-lock.json .
# Install dependencies
RUN npm install

# Command to start the application
CMD ["npm", "start"]