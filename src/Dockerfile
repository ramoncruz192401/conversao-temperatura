FROM node
WORKIDIR /app
COPY packege*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node" , "server.js"]
