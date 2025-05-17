# Simple docker file skeleton

# Base image
FROM node:alpine

# Set working directory
WORKDIR /src

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . .

# Set port environment variable
ENV PORT=9000

# Expose port
EXPOSE 9000

# Run the application
CMD ["npm", "run", "dev"]


