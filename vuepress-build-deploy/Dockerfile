FROM node:10

RUN git clone

# BUILD
RUN npm --prefix histovery-b2b/website install
RUN npm run --prefix histovery-b2b/website build

# DEPLOY
RUN npm -g i firebase-tools
RUN cd histovery-b2b && firebase deploy --token "FIREBASE_TOKEN_HERE"

