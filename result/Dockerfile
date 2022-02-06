FROM node:8.16.0-alpine

WORKDIR /app 

COPY . . 

RUN npm install  && \ 
    npm audit fix 
    
EXPOSE 5000

CMD npm start 
