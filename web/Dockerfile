FROM node:14.17.6
COPY . /work/
WORKDIR /work
RUN yarn global add @vue/cli
RUN yarn install
# RUN yarn run build
EXPOSE 8080
VOLUME /data
CMD ["yarn", "serve"]
