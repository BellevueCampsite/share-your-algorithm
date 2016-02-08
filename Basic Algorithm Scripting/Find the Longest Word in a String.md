# [Find the Longest Word in a String](http://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)

*Return the length of the longest word in the provided sentence. Your response should be a number.*

## Solutions

```javascript
function findLongestWord(str) {
  var myArr = str.split(' ');
  var longestLength = 0;
  for (var i = 0; i < myArr.length; i++) {
    if (myArr[i].length > longestLength) {
      longestLength = myArr[i].length;
    }
  }
  return longestLength;
}

```
