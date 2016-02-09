# [Repeat a string repeat a string](http://www.freecodecamp.com/challenges/repeat-a-string-repeat-a-string)

*Repeat a given string (first argument) num times (second argument). Return an empty string if num is a negative number.*

## Solutions

```javascript
function repeat(str, num) {
  var repeatedStr = "";
  if (num < 0) {
    return repeatedStr;
  } else {
    for (var i = 0; i < num; i++) {
      repeatedStr += str;
    }
  }
  return repeatedStr;
}

```
