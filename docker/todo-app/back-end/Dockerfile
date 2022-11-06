FROM node:14-alpine AS todobackend
WORKDIR /app
ADD node_modules.tar.gz .
COPY . .
RUN npm install
EXPOSE 3001
CMD ["npm", "start"]
