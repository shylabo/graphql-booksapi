# graphql-booksapi

$ npm init

@package.json
#change
"main": "server.js" also make server.js

#install 3modules
$ npm i express express-graphql graphql

$ npm i --save-dev nodemon
#nodemon is a tool that helps develop node.js based applications by automatically restarting the node
#application when file changes in the directory are detected.

@package.json
#remove "test" & change scripts
scripts: {
"dev" : "nodemon server.js"
}

#server start
$ npm run dev

#access
http://localhost:5000/graphql?
