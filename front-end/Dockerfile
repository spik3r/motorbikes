FROM node:alpine
WORKDIR /front-end
COPY package.json ./
COPY ./ ./
RUN yarn install
CMD ["yarn", "start"]