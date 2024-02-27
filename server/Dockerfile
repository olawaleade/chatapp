FROM node:latest
WORKDIR /app
COPY package-lock.json package.json index.js ./
RUN yarn install 
CMD ["yarn","start"]
EXPOSE 3001