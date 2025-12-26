FROM node:20.19.5-alpine3.21 as build
WORKDIR /opt/server
COPY package.json .
COPY *.js .
#This may add extra cache memory
RUN npm install


# FROM node:20
# WORKDIR /opt/server
# EXPOSE 8080
# COPY package.json .
# COPY *.js .
# RUN npm install
# ENV REDIS_HOST="redis" \
#     CATALOGUE_HOST="catalogue" \
#     CATALOGUE_PORT="8080"
# CMD ["node", "server.js"]