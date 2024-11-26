FROM mcr.microsoft.com/playwright:latest

WORKDIR /tests

COPY ./playwrite /tests
RUN npm install

CMD ["npm", "test"]
