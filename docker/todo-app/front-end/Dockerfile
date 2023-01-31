FROM node:14 AS todofrontend
WORKDIR /todo-app/front-end
COPY . .
EXPOSE 3000
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "start" ]
