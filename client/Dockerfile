#using the nodes official latest image by specifying the version
FROM node:18

# Set working directory i.e current folder inside a running Docker container.
WORKDIR /app 

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the entire project
COPY . .

# Expose port (Adjust if necessary)
EXPOSE 5173

# Start the application
CMD ["npm", "run","dev"]
