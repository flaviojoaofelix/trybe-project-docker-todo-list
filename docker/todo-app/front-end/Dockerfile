FROM node:14-alpine AS todofrontend
EXPOSE 3000
ADD node_modules.tar.gz .
WORKDIR /todo-app/back-end/
COPY . .

ENTRYPOINT ["npm", "start"]