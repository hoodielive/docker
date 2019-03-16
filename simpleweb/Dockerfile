# Specify base image 
FROM node:alpine

# specify where to save app
WORKDIR /usr/app

# Place stuff inside of the container 
COPY ./ ./

# Install dependencies 
RUN npm install 

# Setup up default cmd 
CMD ["npm", "start"]
