FROM node:14-alpine AS todofrontend
WORKDIR /app
ADD node_modules.tar.gz .
COPY . .
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]
