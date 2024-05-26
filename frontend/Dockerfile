# Sử dụng image Node.js
FROM node:20 
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
# Cổng website chạy
EXPOSE 3000
# Khởi động website
CMD ["npm","run", "start"]  