FROM node AS build

USER node

COPY --chown=node:node vue /home/node/vue

WORKDIR /home/node/vue

RUN yarn install && \
yarn docker

FROM nginx

COPY http.nginx.conf /etc/nginx/conf.d/default.conf

COPY --chown=root:root --from=build /home/node/vue/dist /usr/share/nginx/html/comoestas

CMD ["nginx", "-g", "daemon off;"]