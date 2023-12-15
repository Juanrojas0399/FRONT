FROM node:alpine

WORKDIR Client/src/app
COPY . .

RUN npm config set legacy-peer-deps true
RUN npm install

CMD ["npm", "run", "build"]
