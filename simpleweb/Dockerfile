# Use an existing docker image as a base
FROM node:alpine

# Download and install a depend
COPY ./ ./
RUN npm install


# Tell the images what do do when it starts as a container
CMD ["npm", "start"]