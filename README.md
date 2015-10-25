# jsTranspilers
Guide and samples for Typescript, Babel, and ES5.

#### Install NodeJs, build essentials and npm on Ubuntu/Debian
```
~$ curl --silent --location https://deb.nodesource.com/setup_4.x | sudo bash -
~$ sudo apt-get install --yes nodejs
~$ sudo apt-get install --yes build-essential
~$ which nodejs
/usr/bin/nodejs
~$ sudo ln -s /usr/bin/nodejs /usr/bin/node
~$ node -v
v0.10.25
~$ sudo apt-get install npm
~$ npm -v
1.4.21
```

## Typescript
### Install Typescript Globally
```
~$ sudo npm install -g typescript
/usr/local/bin/tsc -> /usr/local/lib/node_modules/typescript/bin/tsc
/usr/local/bin/tsserver -> /usr/local/lib/node_modules/typescript/bin/tsserver
typescript@1.6.2 /usr/local/lib/node_modules/typescript
~$ 
```
### Set Typescript transpiler plugin setting on Webstorm10
see screenshot https://goo.gl/LA5pXE
