# CHOOSE IMAGE
FROM node:16.14.2-alpine

#  DIRECTORY
WORKDIR /usr/src/app

# COPY PACKAGE.JSON AND LOCK
COPY package*.json ./

# INSTALL PACKAGE
RUN yarn install
# If you are building your code for production
# RUN npm ci --only=production

# Bundle app source
COPY . .

EXPOSE 3000
CMD [ "node", "bin/www" ]
