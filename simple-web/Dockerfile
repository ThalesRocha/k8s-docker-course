# Specify a base image
FROM node:alpine

# WORKDIR to use in any perfom comand inside th container, if it doesn't exist it will be automatically created
WORKDIR /usr/app

# install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]
