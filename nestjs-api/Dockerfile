FROM node:20-slim

RUN apt update && \
    apt install openssl procps -y && \
    npm install -g @nestjs/cli@10.4.8

# USER node

WORKDIR /app

# CMD [ "tail", "-f", "/dev/null" ]
CMD [ "npm", "run", "start:dev" ]