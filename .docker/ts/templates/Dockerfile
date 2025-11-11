FROM node:{VERSION}-alpine
WORKDIR /usr/src/app
COPY tsconfig.json ./
COPY package.json ./
RUN npm install
CMD ["npx", "ts-node"]
