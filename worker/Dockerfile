FROM node:14.14.0-alpine

WORKDIR '/app'
 
COPY --chown=node:node ./package.json ./
RUN npm install

COPY --chown=node:node ./ ./
 
CMD ["npm", "run", "start"]