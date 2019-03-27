# Specify a base image
# alpine -> most stripped down version of an image
FROM node:alpine 

WORKDIR /usr/app

# Install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]