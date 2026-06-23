# Step 1: Use a Node base image
FROM node:18-alpine

# Step 2: Set the working directory
WORKDIR /app

# Step 3: Copy the package.json and install dependencies
COPY package*.json ./
RUN npm install

# Step 4: Copy the rest of the application files
COPY . .

# Step 5: Expose the port the app will run on
EXPOSE 5000


# Step 7: Start the application
CMD ["npm", "start"]