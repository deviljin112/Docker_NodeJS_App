FROM node:latest
WORKDIR /usr/src/app
COPY . .
RUN npm install
EXPOSE 3000
ENV DB_HOST=172.17.0.2:27017
CMD ["node", "app.js"]
