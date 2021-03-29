FROM node:12.14.0 AS base
COPY ./src ./opt/src/
COPY . ./opt
RUN npm --prefix /opt install
# This command starts up the app
CMD npm  run start 