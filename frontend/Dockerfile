FROM node:14

WORKDIR /app

COPY /src/vite/package.json ./
RUN npm install

COPY . .

CMD ["npm", "start"]