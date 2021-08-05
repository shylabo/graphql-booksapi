# graphql-booksapi

## Description

GraphQL を使って本の名前と著者名を取得する簡易的なサンプルです。

## Install from scratch

```
$ mkdir graphql-booksapi
$ cd graphql-booksapi
$ touch server.js
```

```
$ npm init
$ npm i express express-graphql graphql
$ npm i --save-dev nodemon
```

\*nodemon is a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.

## Edit package.json

```
"main": "server.js"
```

```
scripts: {
		"dev" : "nodemon server.js"
}
```

## server start

```
$ npm run dev
```

Access http://localhost:5000/graphql? in Web browser.
