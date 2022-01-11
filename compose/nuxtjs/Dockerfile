FROM node:16-alpine

WORKDIR /app

COPY ./app/package.json ./app/yarn.lock ./

# If you want to add some new ENVs for the project this is a great place to do it
# ENV ...

ENV HOST 0.0.0.0

COPY ./compose/nuxtjs/entrypoint.sh /usr/local/bin/

COPY ./app .

EXPOSE 3000

ENTRYPOINT ["entrypoint.sh"]

CMD [ "yarn", "dev" ]