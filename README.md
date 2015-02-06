# AFINN-json
Node and JSON version of [AFINN](http://www2.imm.dtu.dk/pubdb/views/publication_details.php?id=6010) - A list of words rated by positive/negative sentiment'. Useful for sentiment analysis. 

##Usage
`AFINN.json` can be used out of the box.  

Or you can access the data in Node:

```javascript
var AFINN = require('./AFINN.js');

var obj = AFINN.AFINNObject(); //Object representation
var json = AFINN.AFINNJSON(); //JSON representation
```
