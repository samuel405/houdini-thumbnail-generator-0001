FROM clearlinux/node:18

WORKDIR /usr/src

COPY . /usr/src

RUN npm ci

EXPOSE 80

CMD ["node", "run", "index.js"]