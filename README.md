# is-valid-json

<img src="https://img.shields.io/badge/npm%20downloads-%3E%20100K-green"></img>
<img src="https://img.shields.io/badge/LICENSE-MIT-green"></img>

----

A small tool to check if a Javscript literal/object is JSON or not

### Installation (as node package)
```sh
npm install is-valid-json --save
```
### Version
1.0.2

### License
MIT

### Usage

```sh
var isJSON = require('is-valid-json');

// "obj" can be {},{"foo":"bar"},2,"2",true,false,null,undefined, etc.
var obj = "any JS literal here";   

if( isJSON(obj) ){

  // Valid JSON, do something
}
else{

  // not a valid JSON, show friendly error message
}
```
