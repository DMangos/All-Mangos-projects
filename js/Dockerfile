FROM node:13-alpine


#Create	the working directory inside the container
WORKDIR /home/js


#Copy all the files to run nodejs for the website
COPY . .


# will execute npm install in /home/js because of WORKDIR
RUN npm install\
    npm install -g eslint


CMD ["node", "./context/packages/eslint-config-airbnb/whitespace-async.js"] 


#,"./context/packages/eslint-config-airbnb-base/whitespace-async.js"]


