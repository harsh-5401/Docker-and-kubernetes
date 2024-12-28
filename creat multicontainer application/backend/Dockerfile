FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

# // DEAFULT VALUES FOR MONGO DB    

ENV MONGO_INITDB_ROOT_USERNAME=username

ENV MONGO_INITDB_ROOT_PASSWORD=password

CMD ["npm", "start"]