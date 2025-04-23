FROM node
WORKDIR /app
COPY package.json /app
RUN npm install
COPY . /app
Expose 7777
CMD ["npm", "run", "start"]