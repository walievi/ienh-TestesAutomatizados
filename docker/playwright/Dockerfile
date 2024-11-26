FROM mcr.microsoft.com/playwright:latest

WORKDIR /tests

COPY ./playwright /tests
RUN npm install

CMD ["npm", "test"]
