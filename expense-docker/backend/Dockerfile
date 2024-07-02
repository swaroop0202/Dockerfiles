FROM node:20
EXPOSE 8080
RUN useradd expense

RUN mkdir -p  /opt/server
RUN chown expense:expense -R /opt/server
RUN npm install
USER expense
WORKDIR /opt/server
COPY package.json .
COPY *.js .


CMD [ "node","index.js" ]

