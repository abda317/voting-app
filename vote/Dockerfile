FROM node:14

WORKDIR /app

RUN git clone https://github.com/dockersamples/example-voting-app.git . && \
    cd vote && npm install && npm run build

WORKDIR /app/vote
CMD ["npm", "start"]
