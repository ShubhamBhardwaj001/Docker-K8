FROM node:18-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install --only=production

COPY . .

EXPOSE 3000
CMD ["node", "index.js"]

### this index.js is the app you should have in your repo only like we creatred in codespace
