#### Code snoppets for working with my editor, inspired by VSCode:
 - [JavaScript (ES6)](https://github.com/xabikos/vscode-javascript)
 - [Reactjs code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets)
 - [REACT TOOLBOX SNIPPETS](https://marketplace.visualstudio.com/items?itemName=alechp.react-toolbox-snippets)

###### Import and export 
__imp__→	imports entire module ```import fs from 'fs'```    
__imd__→	imports only a portion of the module using destructing ```import {rename} from 'fs';```    


###### Various methods
__fre__→	forEach loop in ES6 syntax ```array.forEach(currentItem => {})```   
__fof__→	for ... of loop ```for(let item of object) {}```    
__fin__→	for ... in loop ```for(let item in object) {}```    
__afn__→	creates an anonymous ```function (params) => {}```    
__nfn__→	creates a named function ```const add = (params) => {}```    
__dob__→	desctucting object syntax ```const {rename} = fs```                  
__dar__→	desctucting array syntax ```const [first, second] = [1,2]```    
__sti__→	set interval helper method ```setInterval(() => {});```    
__sto__→	set timeout helper method ```setTimeout(() => {});```    


###### Class helpers
__con__→	adds default constructor in the class ```constructor() {}```
__met__→	creates a method inside a class ```add() {}```
__pge__→	creates a getter property ```get propertyName() {return value;}```
__pse__→	creates a setter property ```set propertyName(value) {}```

###### Console methods
__cer__→	console error ```console.error(object)```
__cgr__→	console group ```console.group(label)```
__cas__→	console allert method ```console.assert(expression, object)```
__cge__→	console groupEnd ```console.groupEnd()```
__cco__→	console count ```console.count(label)```
__ccl__→	console clear ```console.clear()```
__cdi__→	console dir ```console.dir```
__clg__→	console log ```console.log(object)```
__ctr__→	console trace ```console.trace(object)```
__cwa__→	console warn ```console.warn```
