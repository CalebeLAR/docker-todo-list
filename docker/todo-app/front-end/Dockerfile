FROM node:14 AS todofrontend
COPY . .
EXPOSE 3000
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "start" ]
