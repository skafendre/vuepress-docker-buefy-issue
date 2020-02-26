FROM node:latest

RUN git clone

# dev
RUN npm --prefix histovery-b2b/website install
RUN npm --prefix histovery-b2b/website audit fix
CMD ["npm", "run", "--prefix", "histovery-b2b/website", "dev"]

EXPOSE 8080

