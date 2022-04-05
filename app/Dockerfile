# Pull Nodejs
FROM node:17
 
# Set working directory
WORKDIR /src

# Copy app source into the image 
COPY . .

# Install app dependencies 
RUN npm install

# Expose port 3000
EXPOSE 3000

# Run app at start 
CMD ["node", "app.js"]
