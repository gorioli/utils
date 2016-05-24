#### Code snoppets for working with my editor, inspired by VSCode:
 - [JavaScript (ES6)](https://github.com/xabikos/vscode-javascript)
 - [Reactjs code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets)
 - [REACT TOOLBOX SNIPPETS](https://marketplace.visualstudio.com/items?itemName=alechp.react-toolbox-snippets)

###### Import and export 
__imp__→	imports entire module ```import fs from 'fs'```
__imd__→	imports only a portion of the module using destructing ```import {rename} from 'fs';```

###### Various methods
fre→	forEach loop in ES6 syntax array.forEach(currentItem => {})
fof→	for ... of loop for(let item of object) {}
fin→	for ... in loop for(let item in object) {}
afn→	creates an anonymous function (params) => {}
nfn→	creates a named function const add = (params) => {}
dob→	desctucting object syntax const {rename} = fs
dar→	desctucting array syntax const [first, second] = [1,2]
sti→	set interval helper method setInterval(() => {});
sto→	set timeout helper method setTimeout(() => {});

###### Class helpers
con→	adds default constructor in the class constructor() {}
met→	creates a method inside a class add() {}
pge→	creates a getter property get propertyName() {return value;}
pse→	creates a setter property set propertyName(value) {}

###### Console methods
cas→	console allert method console.assert(expression, object)
ccl→	console clear console.clear()
cco→	console count console.count(label)
cdi→	console dir console.dir
cer→	console error console.error(object)
cgr→	console group console.group(label)
cge→	console groupEnd console.groupEnd()
clg→	console log console.log(object)
ctr→	console trace console.trace(object)
cwa→	console warn console.warn
