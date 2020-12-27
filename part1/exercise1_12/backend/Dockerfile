FROM node:10

ENV FRONT_URL=http://localhost:5000
COPY ./backend-example-docker/ ./
EXPOSE 8000

ENTRYPOINT ["npm", "start"]