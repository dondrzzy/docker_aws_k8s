FROM node:14-alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

# pass as args
ENV MONGODB_USERNAME=
ENV MONGODB_PASSWORD=
ENV MONGODB_URL=
ENV MONGODB_NAME=

CMD ["npm", "start"]
