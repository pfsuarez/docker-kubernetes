FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=your_admin_user
ENV MONGODB_PASSWORD=your_admin_password

CMD ["npm", "start"]