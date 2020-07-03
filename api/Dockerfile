FROM node

USER node

COPY --chown=node:node core /home/node/core
COPY --chown=node:node mongodb /home/node/mongodb
COPY --chown=node:node fastify /home/node/comoestas

WORKDIR /home/node/comoestas

RUN cd ../core && \
    yarn install && \
    yarn link && \
    cd ../mongodb && \
    yarn install && \
    yarn link comoestas-core && \
    yarn link && \
    cd ../comoestas && \
    yarn install && \
    yarn link comoestas-core && \
    yarn link comoestas-mongodb 

CMD [ "node","server.js" ]