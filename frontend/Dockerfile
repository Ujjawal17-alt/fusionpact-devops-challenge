FROM node:20-alpine

WORKDIR /app

# Copy package files first for caching
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the frontend code
COPY . .

# Expose port (if using dev server)
EXPOSE 3000

# Start the app
CMD ["npm", "start"]
