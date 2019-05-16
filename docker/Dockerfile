# load node image with verson 10
FROM node:10

# copy local directory to container
COPY . ./

# install dependencies
RUN npm install -g yarn &&\
    yarn

# set container directory
WORKDIR /var/www

# run webserver
CMD ["yarn", "serve"]
