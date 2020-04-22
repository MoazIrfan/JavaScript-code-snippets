# JavaScript Snippets for VS Code

This extension contains code snippets for JavaScript in ES6 syntax.

## Snippets

Type Less & Do More with super easy triggers of code snippets.

List of all the snippets with triggers:

## Console

### [ci] console.info

```javascript
console.info(${1});
```

### [cl] console.log

```javascript
console.log(${1});
```

### [ce] console.error

```javascript
console.error(${1});
```

### [cw] console.warn

```javascript
console.warn(${1});
```

### [cd] console.dir

```javascript
console.dir(${1});
```

## DOM

### [ae] addEventListener

```javascript
${1:document}.addEventListener('${2:load}', (e) => {
	${3:// body}
});
```

### [ac] appendChild

```javascript
${1:document}.appendChild(${2:elem});
```

### [rc] removeChild

```javascript
${1:document}.removeChild(${2:elem});
```

### [cel] createElement

```javascript
${1:document}.createElement(${2:elem});
```

### [cdf] createDocumentFragment

```javascript
${1:document}.createDocumentFragment();
```

### [ca] classList.add

```javascript
${1:document}.classList.add('${2:class}');
```

### [ct] classList.toggle

```javascript
${1:document}.classList.toggle('${2:class}');
```

### [cr] classList.remove

```javascript
${1:document}.classList.remove('${2:class}');
```

### [gi] getElementById

```javascript
${1:document}.getElementById('${2:id}');
```

### [gc] getElementsByClassName

```javascript
${1:document}.getElementsByClassName('${2:class}');
```

### [gt] getElementsByTagName

```javascript
${1:document}.getElementsByTagName('${2:tag}');
```

### [ga] getAttribute

```javascript
${1:document}.getAttribute('${2:attr}');
```

### [sa] setAttribute

```javascript
${1:document}.setAttribute('${2:attr}', ${3:value});
```

### [ra] removeAttribute

```javascript
${1:document}.removeAttribute('${2:attr}');
```

### [ih] innerHTML

```javascript
${1:document}.innerHTML = '${2:elem}';
```

### [tc] textContent

```javascript
${1:document}.textContent = '${2:content}';
```

### [qs] querySelector

```javascript
${1:document}.querySelector('${2:selector}');
```

### [qsa] querySelectorAll

```javascript
${1:document}.querySelectorAll('${2:selector}');
```

## Loop

### [fl] for loop
```javascript
for (let ${1:i} = 0, ${2:len} = ${3:iterable}.length; ${1:i} < ${2:len}; ${1:i}++) {
	${0}
}
```

### [rfl] reverse for loop
```javascript
for (let ${1:i} = ${2:iterable}.length - 1; ${1:i} >= 0; ${1:i}--) {
	${0}
}
```

### [fi] for in loop
```javascript
for (let ${1:key} in ${2:array}) {
	if (${2:array}.hasOwnProperty(${1:key})) {
		${0}
	}
}
```

},
### [fo] for of loop (ES6)
```javascript
for (let ${1:key} of ${2:array}) {
	${0}
}
```

### [wl] while loop
```javascript
while (${1:condition}) {
	${0}
}
```
## Functions

### [f] anonymous function
```javascript
function (${1:arguments}) {
	${0}
}
```

### [fn] named function
```javascript
function ${1:name}(${2:arguments}) {
	${0}
}
```

### [iife] immediately-invoked function expression (IIFE)
```javascript
((${1:arguments}) => {
	${0}
})(${2});
```

### [fa] function apply
```javascript
${1:fn}.apply(${2:this}, ${3:arguments})
```

### [fc] function call
```javascript
${1:fn}.call(${2:this}, ${3:arguments})
```

### [fb] function bind
```javascript
${1:fn}.bind(${2:this}, ${3:arguments})
```

### `[af] arrow function (ES6)
```javascript
(${1:arguments}) => ${2:statement}
```

### [afb] arrow function with body (ES6)
```javascript
(${1:arguments}) => {
	${0}
}
```

### [gf] generator function (ES6)
```javascript
function* (${1:arguments}) {
	${0}
}
```

### [gfn] named generator function (ES6)
```javascript
function* ${1:name}(${2:arguments}) {
	${0}
}
```

## Iterables

### [seq] sequence of 0..n
```javascript
[...Array(${1:length}).keys()]${0}
```

### [fe] forEach loop
```javascript
${1}.forEach((${2:item}) => {
	${0}
});
```

### [map] map
```javascript
${1}.map((${2:item}) => {
	${0}
});
```

### [reduce] reduce
```javascript
${1}.reduce((${2:previous}, ${3:current}) => {
	${0}
}${4:, initial});
```

### [filter] filter
```javascript
${1}.filter(${2:item} => {
	${0}
});
```

### [find] find
```javascript
${1}.find(${2:item} => {
	${0}
});
```
## JSON

### [jp] JSON.parse

```javascript
JSON.parse(${1:obj});
```

### [js] JSON.stringify

```javascript
JSON.stringify(${1:obj});
```

## Timer

### [si] setInterval

```javascript
setInterval(function() {
	${0:// body}
}, ${1:1000});
```

### [st] setTimeout

```javascript
setTimeout(function() {
	${0:// body}
}, ${1:1000});
```

## Misc

### [us] use strict

```javascript
'use strict';
```

### [al] alert

```javascript
alert('${1:msg}');
```

### [co] confirm

```javascript
confirm('${1:msg}');
```

### [pm] prompt

```javascript
prompt('${1:msg}');
```
### [ter] ternary operator
```javascript
${1:condition} ? ${2:expression} : ${3:expression};
```
### [de] debugger

```javascript
debugger;
```