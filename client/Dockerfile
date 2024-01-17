FROM node:18 AS development

WORKDIR /app

COPY ./package*.json ./

RUN npm install

COPY . .

EXPOSE 80

CMD [ "npm", "run", "esposed" ] 