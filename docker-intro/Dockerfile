FROM node:latest

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE  80

# CMD command is user to RUN the command when a container is created ( alternate for RUN so that command wont be executed while creating docker image)
CMD ["node", "server.js"]