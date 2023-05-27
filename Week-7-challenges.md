# Week challenges (Monday) 💻

## 1. String: substr()
```JavaScript
function firstWord(chain) {
 let space = chain.indexOf(" ");
 return chain.substr(0, space);
}
```
## 2. String: replace()
```JavaScript
function normalize(chain) {
let res = '';

for(let i = 0; i < chain.length; i++) {
 if(chain[i] === '-') {
   res = res + chain[i].replace('-','/');
}else {
 res = res + chain[i];
}
}
return res;
}
```
## 3. Increment
```JavaScript
// The value of x is 7
```

## 4. Fahrenheit
```JavaScript
function toFahrenheit(num) {
  return (parseInt(num) * (9/5)) + 32
}
```
## 5. Boolean
```JavaScript
function nand(val1, val2) {
  if(val1 && val2){ 
    return false;
}
return true;
}
```

# Week challenges (Tuesday) 💻

## 2. Objects
```JavaScript
function animal(obj){
  return `This ${obj.color} ${obj.name} has ${obj.legs} legs.`;
}
```
## 3. Return to sanity
```JavaScript
function mystery() {
  var results =
    {sanity: 'Hello'};
  return results;
}
```
## 4. Object syntax debug
```JavaScript
var rooms = {
   first : {
    description: 'This is the first room',
    items: {
      chair: 'The old chair looks comfortable',
      lamp: 'This lamp looks ancient',
      }
  },
  second : {
    description: 'This is the second room',
    items: {
      couch: 'This couch looks like it would hurt your back',
      table: 'On the table there is an unopened bottle of water'
    }
  }
}
```
# Week challenges (Wednesday) 💻

## 1. Count strings in objects
```JavaScript
function strCount(obj){
  
  const valueLength = Object.values(obj)
  let arr = []
 
  for(let i = 0; i < valueLength.length; i++) {
    
    if(typeof valueLength[i] === 'string') {
        arr.push(valueLength[i])
    } else if (Array.isArray(valueLength[i])) {
      arr = arr.concat(valueLength[i].filter(value => typeof value === 'string'))
    }
  }  
  return arr.length;
}
```
## 2. Extending JavaScript Objects: Get First & Last Array Element
```JavaScript
Array.prototype.first = function() {
  if(this.length > 0) {
    return this[0];
  }
  
  return undefined;
}

Array.prototype.last = function() {
  if(this.length > 0) {
    return this[this.length - 1];
  }
  
  return undefined;
}
```
## 3. Object Oriented Piracy
```JavaScript

```

# Week challenges (Thursday) 💻

## 1. Convert a String to a Number!
```JavaScript

```
## 2. Convert number to reversed array of digits
```JavaScript

```
## 3. Truthy and Falsy
```JavaScript

```
## 4. Training JS #4: Basic data types--Array
```JavaScript

```
