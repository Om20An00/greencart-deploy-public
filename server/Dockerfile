FROM node:18

WORKDIR /app

# Copy dependency files
COPY package*.json ./

# Install dependencies (prod + dev is fine for nodemon, but we only need prod in container)
RUN npm install --production

# Copy the rest of your server code
COPY . .

# Expose port
EXPOSE 4000

# Start the server with the start script
CMD ["npm", "start"]
