koa-fun
=======

Some funs with Koa.js 

## Install

#### Node v0.11
[Koa.js](http://koajs.com/#application) is a framework which relies on Node.js >=0.11.9. It's likely that you'll need to install this unstable version of node.js. 

For Mac OS X users follow these steps:

1. `brew install nvm`
2. Add nvm to your appropriate `.zshrc` or `.bashrc` file: `source $(brew --prefix nvm)/nvm.sh`
3. `nvm install -g 0.11.9`


This should set you up with node v0.11.9.

#### Node Harmony
Koa.js uses experimental features in the node project which means the developer will have to run node with the `harmony` flag

1. `npm install`
2. `node --harmony app.js`


### Check your browser
Hopefully everything has gone well and you can now visit [http://127.0.0.1:3000/](http://127.0.0.1:3000/) and see your node server running.
