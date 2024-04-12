FROM node:20.12.1

WORKDIR /app

COPY ../package.json ./
COPY ../yarn.lock ./

RUN yarn install --frozen-lockfile

COPY .. .

CMD ["yarn", "start"]
