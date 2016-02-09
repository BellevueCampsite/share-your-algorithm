# [Confirm the Ending](http://www.freecodecamp.com/challenges/confirm-the-ending)

*Check if a string (first argument) ends with the given target string (second argument).*

## Solutions

```javascript
function end(str, target) {
  return str.substr(-target.length, target.length) === target;
}

```
