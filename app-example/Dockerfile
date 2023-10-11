# download node in docker hub
FROM node:14
# set workfolder to work on it 
WORKDIR /app-node
# copys node information at actual folder (/node-example) in to /app-node
COPY . /app-node
# command that is used when image is beeing created
RUN npm install
# when this image has already been created runs this command
ENTRYPOINT  npm start