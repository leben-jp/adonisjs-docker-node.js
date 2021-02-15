# Docker-node.js

![nodejsanddocker](./images/nodejsanddocker.jpeg)

## Features

- Automatically restarts the Node.js process
- Support remote debugging
- Customize the configuration file
- Data is stored in the host

 
## Software Stack
- [x] AdonisJS
- [x] MongoDB
- [x] Redis
- [x] MySQL
- [x] Node.js 7.x
- [x] Nginx with LuaJit
- [x] Nodemon

#### Requirements

- [Docker](https://www.docker.com/)

- [Docker-compose](https://github.com/docker/compose/releases)

>Windows and Mac users only need to install Docker

#### Getting started

```bash

git clone https://github.com/huangyanxiong01/docker-node.js.git

cd docker-node.js

yarn install

docker-compose up -d

docker exec -i -t docker-nodejs_node_1 bash

npm i -g @adonisjs/cli

adonis new adonis-app

adonis serve --dev

Now,you can open http://0.0.0.0:33333/ in browser
```
