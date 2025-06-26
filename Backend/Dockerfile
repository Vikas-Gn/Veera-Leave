# Use Node.js base image
FROM node:20

# Set working directory
WORKDIR /app

# Copy dependencies
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy rest of the code
COPY . .

# Expose backend port
EXPOSE 3059

# Run the server
CMD ["node", "Server.js"]

