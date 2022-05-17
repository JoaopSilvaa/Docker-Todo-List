FROM node:14-alpine
WORKDIR /todo-app/back-end/src
EXPOSE 3001
COPY node_modules.tar.gz ./
RUN ['gunzip' 'node_modules.tar.gz']
COPY . .
ENTRYPOINT [ "npm", "start" ]
