
```dataviewjs 
let docs = dv.pages('"Межкультурное взаим"'); 
let length = docs.length; 
let numberToReturn = 1; 
var randos = getRandos(docs, length, numberToReturn); 
dv.span('!'+randos); 
function getRandos(list, max, itemNum) 
{ 
	var items = [];
	for (var i=0;i<itemNum;i++){ 
	items.push(
		list[
			Math.floor(Math.random() * max)
			].file.link
			); 
			} return items; }
```

