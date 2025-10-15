# Use a Node.js image (example for frontend)
FROM node:20-alpine

# Set working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the frontend code
COPY . .

# Expose port
EXPOSE 3000

# Start the app
CMD ["npm", "start"]
