# Dockerfile for frontend
FROM node:16 AS build

# Set the working directory
WORKDIR /usr/src/app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application files
COPY . .

# Build the application
RUN npm run build

# Serve the application using node
FROM node:16

# Set the working directory
WORKDIR /usr/src/app

# Install serve package globally
RUN npm install -g serve

# Copy build output from previous stage
COPY --from=build /usr/src/app/dist ./build

# Expose the port on which the app will run
EXPOSE 3000

# Command to run the app
CMD ["serve", "-s", "build"]
