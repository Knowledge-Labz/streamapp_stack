FROM node:latest
USER root

RUN mkdir /var/nms
COPY ./app.js /var/nms/app.js
RUN cd /var/nms && npm install node-media-server
ENTRYPOINT ["node", "/var/nms/app.js"]