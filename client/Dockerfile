# Step 1: Use a Node base image
FROM node:18-alpine AS build

# Step 2: Set the working directory in the container
WORKDIR /app

# Step 3: Copy the package.json and install dependencies
COPY package*.json ./
RUN npm install

# Step 4: Copy the rest of the application files
COPY . .

# Step 5: Build the React app for production
RUN npm run build

#Stage 2 

FROM nginx:alpine

COPY --from=build /app/dist /usr/share/nginx/html

EXPOSE 5173 

CMD ["nginx", "-g", "daemon off;"]