FROM node:12
COPY ./frontend /app/frontend
WORKDIR /app/frontend
RUN yarn
RUN yarn add create-nuxt-app
CMD ["yarn", "dev"]
