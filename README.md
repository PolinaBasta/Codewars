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