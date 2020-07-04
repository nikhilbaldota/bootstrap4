# bootstrap4

How to setup project from stratch

1. Setup node.js & npm
2. Then execute 'npm init' in your project directory -> fill in values (mostly follow defaults) -> This would create package.json file
3. Install an NPM module, lite-server, that allows you to run a Node.js based development web server and serve up your project files. Execute 'npm install lite-server --save-dev' to install.
4. Install bootstrap, jquery, popper.js using commands -
npm install bootstrap@4.0.0 --save
npm install jquery@3.3.1 popper.js@1.12.9 --save
5. You are ready to start with the development. Refer index.html for basics of including the node_modules installed etc.
6. Modify   "scripts": {} in package.json file execute some npm module which would ease development, build & deployment.
7. Some dependencies can be installed globally like
npm -g install copyfiles@2.0.0
npm -g install imagemin-cli@3.0.0

How to run the project

1. Setup node.js & npm
2. Go to the conFusion folder
3. Run command npm install
4. Run command npm start