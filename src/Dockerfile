FROM node:18.11.0
#workdir eh criar um diretorio de trabalho
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . . 
#para expor a porta 8080, a aplicacao utiliza esta porta. No final do "server.js" tem a porta descriminada.
EXPOSE 8080
CMD ["node", "server.js"]