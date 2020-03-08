#specify a base image
FROM node:alpine

#npm install
COPY ./ ./
RUN npm install

#default command
CMD ["npm", "start"]
