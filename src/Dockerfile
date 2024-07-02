#1.Development Vue App for locall
#PULL the baseImage

FROM node:20.15.0-alpine

#SET the Working directory: /USR/app = ./
WORKDIR /usr/app/

COPY ./package.json ./

#Installation dependencies
RUN npm install

#Copy code from host to container
COPY . .

EXPOSE 80

#Deploy app local Development
CMD [ "npm", "run","dev", ]