FROM node:14-alpine
WORKDIR /todo-app/back-end
ADD ./node_modules.tar.gz .
COPY . .
RUN npm install
CMD [ "npm", "start" ]
EXPOSE 3001