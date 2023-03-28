FROM node:14
WORKDIR /app
ADD node_modules.tar.gz ./
COPY package*.json ./
COPY . .
EXPOSE 3001
ENTRYPOINT [ "npm"]
CMD [ "start" ]