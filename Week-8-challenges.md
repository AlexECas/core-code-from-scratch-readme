# Week challenges (Monday) 💻

## 1. Training JS #7: if..else and ternary operator
```JavaScript
function saleHotdogs(n){
  if(n >= 5 && n < 10) {
    return (95 * n);
  }else if (n >= 10) {
    return (90 * n);
  }else {
    return (100 * n);
  }
}
```
## 2. Training JS #8: Conditional statement--switch
```JavaScript
function howManydays(month){
  var days;
  switch (month){
    case 1:
    case 3:
    case 5:
    case 7:
    case 8:
    case 10:
    case 12:
      days = 31;
    break;
    case 4:
    case 6:
    case 9:
    case 11:
      days = 30;
    break;
    case 2:
      days = 28
    break;
  }
  return days;
}
```
## 3. Basic calculator
```JavaScript
function calculate(num1, operation, num2) {
  switch(operation) {
      case '+':
       return num1 + num2;
      break;
      case '-':
       return num1 - num2;
      break;
      case '*':
       return num1 * num2;
      break;
      case '/':
       return (num2 !== 0) ? num1 / num2 : null
      break;
      default:
       return null;
  }
}
```

# Week challenges (Tuesday) 💻

## 1. Even or odd
```JavaScript
function evenOrOdd(number) {
  if(number % 2 === 0) return 'Even'
  else return 'Odd'
}
```
## 2. A wolf in sheep's clothing
```JavaScript
function warnTheSheep(queue) {
  let count = 0;
  for(let i = queue.length - 1; i >= 0; i--) {  
  count++;
  if(queue[queue.length - 1] === 'wolf') {
    return "Pls go away and stop eating my sheep"
  } else if (queue[i] === 'wolf') {
    return `Oi! Sheep number ${count - 1}! You are about to be eaten by a wolf!` 
  }
  }
}
```
## 3. Decode the morse code
```JavaScript
```

# Week challenges (Wednesday) 💻

## 1. Who likes it?
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
## 2. Bit counting
```JavaScript
var countBits = function(n) {
  
  if(n > 0) {
    const arr = n.toString(2).split('');
    
    return (arr.filter(element => element === '1')).length
  }
  
  return 0
};
```
## 3. Your order, please
```JavaScript
function order(words){
  if(words.length > 0) {
    const arr = words.split(' ');
    let res = '';
    let num = 1;
    
    while(num <= arr.length) {
      res += arr.filter((e) => e.includes(num.toString())) + ' ';
      num++;
    }
    
    return res.trim();  
  }
  
  return '';
}
```

# Week challenges (Thursday) 💻

## 1. Counting duplicates
```JavaScript
function duplicateCount(text){
  text = text.toLowerCase();
    
  if(text.length > 0) {
    const arr = text.split('');
    let repeatedValue = '';
    let count = 0;
    
    arr.forEach(element => {
      if((text.indexOf(element) !== text.lastIndexOf(element)) && !repeatedValue.includes(element)) {
        repeatedValue += element;
        count++;
      }
    })
    return count; 
  }
  return 0;
}
```
## 2. Encrypt this!
```JavaScript
var encryptThis = function(text) {
  const arr = text.split(' ');
  
  let res = '';
  
  arr.forEach((element) => {
    const arr2 = element.split('');
    res += ' '
    
    if(arr2.length >= 3) {
      const temp = arr2[1];
      arr2[1] = arr2[arr2.length - 1];
      arr2[arr2.length - 1] = temp;
    }
    
    arr2.forEach((element2, idx) => {
      if(idx === 0) {
        res += element2.charCodeAt(idx)  
      }else {
        res += element2
      }           
    });
    
  });
  
  return res.trim();
}
```
## 3. Valid parentheses
```JavaScript
```
## 4. Convert string to camel case
```JavaScript
```
