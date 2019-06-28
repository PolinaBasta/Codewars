Capitalization and Mutability

https://www.codewars.com/kata/595970246c9b8fa0a8000086

```javascript


function capitalizeWord(word) {
  let newWord = word[0].toUpperCase();
  for (i = 1; i < word.length; i++){
  newWord += word[i];
  }
  return newWord;
}
```
Count the Monkeys!
https://www.codewars.com/kata/count-the-monkeys/javascript
```javascript
function monkeyCount(n) {
let arr = [];
for (let i =1; i <= n; i++){
arr.push(i);
}return arr;// your code here
}
```

= Switch it Up! =
https://www.codewars.com/kata/switch-it-up/train/javascript
```javascript
function switchItUp(number) {
  switch (number) {
    case 0: return 'Zero';
    case 1: return 'One';
    case 2: return 'Two';
    case 3: return 'Three';
    case 4: return 'Four';
    case 5: return 'Five';
    case 6: return 'Six';
    case 7: return 'Seven';
    case 8: return 'Eight';
    case 9: return 'Nine';
  }
}

Get list sum recursively - 7 kyu
https://www.codewars.com/kata/57a84137cf1fa5f9f80000d6
```javascript
function sumR(x) {
  if (x.length === 0) {
    return 0;
  }
  return x[0] + sumR(x.slice(1));
}
```


```