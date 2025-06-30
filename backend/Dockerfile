# Use Node.js base image
FROM node:18-alpine

# Set working directory
WORKDIR /app

# Copy dependencies
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy rest of the code
COPY . .

# Expose port (adjust to your backend server port)
EXPOSE 5000

# Start the server
CMD ["node", "server.js"]
