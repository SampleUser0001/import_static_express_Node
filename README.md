# import_static_express_Node

expressでstaticファイルをimportする

## 実装

- [index.js](./app/src/index.js)

``` javascript
'use strict'

const express = require("express")
const app = express()

app.use('/', express.static(__dirname + '/../html'));
app.listen(3000)
```

## 起動

``` sh
npm install
npm start
```

## URL

[http://localhost:3000](http://localhost:3000)

