FROM node:14

WORKDIR /app

COPY ./package.json .

RUN npm install

COPY . .

EXPOSE 80

# ENV MONGODB_USERNAME=test
# ENV MONGODB_PASSWORD=secret

CMD [ "node", "app.js" ]
