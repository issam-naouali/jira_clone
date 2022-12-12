FROM node:16 AS Client
WORKDIR /usr/src/client 
COPY package.json .
COPY package-lock.json .
RUN npm install
COPY . .
RUN npm run build
CMD ["npm run start"]
