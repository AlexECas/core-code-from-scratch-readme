# Week challenges (Monday) 💻

## 1. "this" is a problem
```JavaScript
function NameMe(first, last) {
    this.firstName = first;
    this.lastName = last;
    return {name: this.firstName + ' ' + this.lastName, firstName: this.firstName, lastName: this.lastName };
}
```
## 2. "Thinkful - List and Loop Drills: Lists of lists"
```JavaScript
function processData(data){
  
  const arr = [];
  
  data.forEach(array => {
    const res = array.reduce((acc, curr) => {
      return acc -= curr;
    }) 
    
    arr.push(res);
  })
  let res2 = 1;
  
  arr.map(e => res2 = res2 * e);
  
  return res2;
}
```
## 3. Stop gninnipS My sdroW!
```JavaScript
function spinWords(string){
  const arr =  string.split(' ');
  const  res = [];
  
  arr.forEach(element => {
    if(element.length >= 5){
      const arr2 = element.split('');
      res.push(arr2.reverse().join(''));
    }else {
      res.push(element);
    }
  })
  return res.join(' ');
}
```

# Week challenges (Tuesday) 💻

## 1. "this" is an other problem
```JavaScript

```
## 2. "Who likes it?"
```JavaScript
function likes(names) {
  
  if(names.length > 0) {
    
    if(names.length >= 2 && names.length <= 3) {
      
      let res = names.reduce((acc, cur, idx) => {
  
        return (idx === (names.length - 1)) ? 
          `${acc} and ${cur} like this` 
          : 
          `${acc}, ${cur}`
        
      });

      return res;
      
    }else if (names.length === 1) {
      return `${names[0]} likes this`;
    }else {
      return  `${names[0]}, ${names[1]} and ${names.length - 2} others like this`;
    }
  
  }
  
  return 'no one likes this'
}
```
## 3. Convert string to camel case
```JavaScript

```

# Week challenges (Wednesday) 💻

## 1. Easy mathematical callback
```JavaScript

```
## 2. Moving Zeros To The End
```JavaScript

```
## 3. Valid Parentheses
```JavaScript

```

# Week challenges (Thursday) 💻

## 1. The Hashtag Generator
```JavaScript

```
## 2. MString incrementer
```JavaScript

```
