# 1. Use official Node image
FROM node:18

# 2. Set working directory
WORKDIR /app

# 3. Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# 4. Copy the full backend code
COPY . .

# 5. Expose backend port
EXPOSE 8080

# 6. Start the server
CMD ["node", "server.js"]
