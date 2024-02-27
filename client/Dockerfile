FROM node:latest
WORKDIR /app
COPY ./public ./public
COPY ./src ./src
COPY package-lock.json package.json ./
RUN yarn install 
CMD ["yarn","start"]
EXPOSE 3000