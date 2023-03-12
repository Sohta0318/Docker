FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV PORT 80

EXPOSE $POST

# VOLUME [ "/app/node_module" ]

# VOLUME [ "/app/feedback" ]

CMD [ "npm", "start" ]