# [Title Case a Sentence](http://www.freecodecamp.com/challenges/title-case-a-sentence)

*Return the provided string with the first letter of each word capitalized. Make sure the rest of the word is in lower case. For the purpose of this exercise, you should also capitalize connecting words like "the" and "of".*

## Solutions

```javascript
function titleCase(str) {
  var wordArr = str.toLowerCase().split(' ');
  var wordArrNew = [];
  for (var i = 0; i < wordArr.length; i++); {
    var charArr = wordArr[i].split('');
    charArr[0] = charArr[0].toUpperCase();
    wordArrNew.push(charArr.join(''));
  }
  return wordArrNew.join(' ');
}

```
