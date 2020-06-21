FROM node:13

WORKDIR /app

COPY package.json ./
COPY package-lock.json ./

RUN npm install
RUN npm install -g react-scripts@3.4.1

COPY . ./

CMD ["npm", "start"]

EXPOSE 3000