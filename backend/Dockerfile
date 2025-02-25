# Use the best node js image
FROM node:18-alpine

# Set working directory ie /app
WORKDIR /app

# Copy the package.json file to the current app direactory and install dependencies
COPY package.json ./
RUN npm install

# Copy the source code to the app directory
COPY . ./

# Expose the port and start the application
EXPOSE 5000
CMD ["npm", "start"]