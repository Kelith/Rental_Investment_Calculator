FROM node:alpine

WORKDIR /rentalsanalysis
COPY . /rentalsanalysis

EXPOSE 3003

RUN npm install -g npm@latest
RUN rm -rf node_modules
RUN npm install
CMD ["npm", "run", "start"]
