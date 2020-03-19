FROM node:8
RUN mkdir /usr/EmployeeDB
WORKDIR /usr/EmployeeDB
RUN chown -R node:node /usr/EmployeeDB
#install app dependencies
COPY . .
RUN npm install express -g
EXPOSE 3000
CMD ["node","app.js"]
