FROM node:10

# RUN apt-get update && apt-get install libpng12-0 bzip2

# Create app directory
WORKDIR /usr/src/app

COPY . .

RUN yarn install

RUN yarn build

CMD ["yarn", "start:prod"]
