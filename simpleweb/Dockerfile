# Use an existing docker image as a base
FROM node:alpine

# Adding a specific working directory. If it does not exist, it will be automatically created
WORKDIR /usr/app

# Copy only package.json, because we want to run npm install command below only if there are changes
# in this particular file 
COPY ./package.json ./

# Download and install a dependency
RUN npm install

COPY ./ ./

# Tell the images what do do when it starts as a container
CMD ["npm", "start"]