# Specify a base image 
FROM  node:alpine

WORKDIR /usr/app

# Install some dependencies
COPY ./package.json ./
RUN npm install
COPY  ./ ./ 

# Defaulf command 
CMD ["npm", "start"]