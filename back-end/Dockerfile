FROM node:alpine
WORKDIR /back-end
COPY package.json ./
COPY ./ ./
RUN yarn install
CMD ["yarn", "start:ts-node-dev"]