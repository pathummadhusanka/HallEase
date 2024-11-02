# Dockerfile for backend
FROM node:16

# Set the working directory
WORKDIR /usr/src/app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application files
COPY . .

# Expose the port on which the app runs
EXPOSE 5000

# Start the application
CMD ["npm", "start"]
