FROM node:16-alpine

WORKDIR /app/front-end

ADD node_modules.tar.gz .

COPY . .

EXPOSE 3000

ENTRYPOINT [ "npm" ]

CMD [ "start" ]