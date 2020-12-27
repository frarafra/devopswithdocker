FROM node:10

ENV API_URL=http://localhost:8888
COPY ./frontend-example-docker/ ./
EXPOSE 5000

ENTRYPOINT ["npm", "start"]