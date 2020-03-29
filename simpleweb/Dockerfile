# Use an existing docker image as a base
FROM node:alpine

# Adding a specific working directory. If it does not exist, it will be automatically created
WORKDIR /usr/app

# Download and install a dependency
COPY ./ ./
RUN npm install

# Tell the images what do do when it starts as a container
CMD ["npm", "start"]