# Start with the Node Image the number 12.16.3 is the tag
FROM node:12.16.3

WORKDIR /code

ENV PORT 80

# copy pac to the Image 
COPY package.json /code/package.json

RUN npm install 

# copy Global dir to local dir
COPY . /code

# command when Running my Image 
CMD ["node", "src/server.js"]

