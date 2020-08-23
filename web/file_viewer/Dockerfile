FROM node:14
RUN npm i -g typescript tslint mocha nodemon forever
EXPOSE 3000
ADD . /app/file_viewer
WORKDIR /app/file_viewer
CMD ['npm', 'run', 'start']