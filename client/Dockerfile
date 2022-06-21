FROM node:12.16.2
ENV REACT_APP_API_URL='http://localhost:3000/api'
WORKDIR /usr/src/app
COPY . /usr/src/app/
RUN npm install
RUN ls /usr/src/app
RUN ls /usr/src/app/public
EXPOSE 4100
CMD npm start