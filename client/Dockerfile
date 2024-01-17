FROM node:lts AS development

WORKDIR /app

COPY ./package*.json ./

RUN npm install

COPY . .

EXPOSE 80

CMD [ "npm", "run", "esposed" ] 