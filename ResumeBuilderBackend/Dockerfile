FROM node:18

WORKDIR /app

COPY . .

RUN npm -f install 
RUN npm install -g typescript

RUN tsc --build

EXPOSE 4292

CMD ["npm","run","start"]

