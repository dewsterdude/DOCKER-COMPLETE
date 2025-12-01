FROM node:14 


WORKDIR /app

COPY package.json .  

RUN npm install    

COPY . .    

ARG DEFAULT_PORT=8ENV PORT=$DEFAULT_PORT

EXPOSE $PORT

CMD ["npm", "start"]  
