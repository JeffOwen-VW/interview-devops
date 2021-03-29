FROM node:12.14.0 AS base
COPY ./src ./opt/src/
COPY . ./opt

# This command starts up the app
CMD npm --prefix /opt run start 