FROM node:14-alpine

WORKDIR /app

ENV TASKS_DIR=/app/tasks
RUN mkdir $TASKS_DIR

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8000

CMD [ "node", "tasks-app.js" ]
