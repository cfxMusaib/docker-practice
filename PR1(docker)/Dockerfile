# Base image
FROM node:alpine

WORKDIR /usr/app

# Install dependicies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default commands
CMD ["npm","start"]