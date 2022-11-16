FROM node:alpine3.10

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=dennis
ENV MONGODB_PASSWORD=secret1234
ENV MONGODB_URL=mongodb
ENV MONGODB_DATABASE=course-goals

CMD ["npm", "start"]