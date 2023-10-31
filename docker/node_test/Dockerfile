FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

# COPY [project path] [container path] 
COPY . /app


EXPOSE 80

CMD ["node", "server.js"]