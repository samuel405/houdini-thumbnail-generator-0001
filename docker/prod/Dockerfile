FROM clearlinux/node:16

WORKDIR /usr/src

COPY . /usr/src

RUN npm ci

EXPOSE 80

CMD ["node", "index.js"]