FROM node:14.17.0-alpine as production
WORKDIR /app
COPY package*.json ./
RUN npm install
RUN yarn install
COPY . .
EXPOSE 8080
CMD ["node"]
