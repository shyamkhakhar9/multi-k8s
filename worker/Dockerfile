FROM node:alpine
WORKDIR '/app/checkpoint'
COPY ./package.json ./
RUN npm install
COPY ./ ./
CMD ["npm", "run", "start"]

