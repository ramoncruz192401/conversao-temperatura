FROM node:18.11.0
WORKIDIR /app
COPY packege*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node" , "server.js"]
