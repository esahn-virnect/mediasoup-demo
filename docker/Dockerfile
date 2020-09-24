FROM node:12

RUN git clone https://github.com/versatica/mediasoup-demo.git && \
    cd mediasoup-demo && \
    git checkout v3 && \
    cd server && \
    npm install && \
    cd ../app && \
    npm install

WORKDIR /mediasoup-demo/server
