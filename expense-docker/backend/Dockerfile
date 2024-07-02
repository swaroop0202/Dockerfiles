FROM node:20
EXPOSE 8080
RUN useradd expense

RUN mkdir -p  /opt/server
RUN chown expense:expense -R /opt/server
USER expense
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install -y
CMD [ "node","index.js" ]

