FROM node:stretch

WORKDIR /usr/src

RUN git clone https://github.com/ahfarmer/calculator.git

WORKDIR /usr/src/calculator

RUN npm install

EXPOSE 3000

ENTRYPOINT ["npm","start"]
