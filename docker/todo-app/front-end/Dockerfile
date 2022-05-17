FROM node:14-alpine
EXPOSE 3000
COPY node_modules.tar.gz ./
RUN ['gunzip' 'node_modules.tar.gz']
COPY . .
ENTRYPOINT [ "npm", "start" ]
