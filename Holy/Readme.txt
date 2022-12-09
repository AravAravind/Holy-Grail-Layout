docker run -p 6379:6379 --name dockera-redis -d redis
node index.js
index.js

var express = require("express");
var app = express();


app.use(express.static('public'));
app.listen(3000,function(){
  console.log('Running on port :3000')
})

var express = require("express");
var app = express();


app.use(express.static('public'));
app.listen(3000,function(){
  console.log('Running on port :3000')
})

