FROM node:14 AS todobackend
COPY . .
EXPOSE 3001
ADD node_modules.tar.gz .
ENTRYPOINT [ "npm", "start" ]
