FROM node:16-alpine

RUN mkdir /app/
WORKDIR /app/

COPY ./ ./

RUN npm install
RUN npm run build

EXPOSE 80
CMD ["npm","run","start"]
