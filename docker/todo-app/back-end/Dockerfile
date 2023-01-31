FROM node:14 AS todobackend
WORKDIR /todo-app/back-end
COPY . .
EXPOSE 3001
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "start" ]
