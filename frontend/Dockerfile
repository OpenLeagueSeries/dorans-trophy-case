FROM node

ENV CHOKIDAR_USEPOLLING true

WORKDIR /app/frontend
COPY package.json /app/frontend

RUN npm install

EXPOSE 3000
CMD ["npm", "start"]
