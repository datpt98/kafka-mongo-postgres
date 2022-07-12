FROM node:16.9.0-alpine
WORKDIR /app
COPY index.js package.json /app/
RUN npm install
RUN npm i -g nodemon
CMD ["nodemon", "index.js"]