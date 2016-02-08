# [Factorialize a Number](http://www.freecodecamp.com/challenges/factorialize-a-number)

*Return the factorial of the provided integer.*

## Solutions

```javascript
function factorialize(num) {
  var i = 1;
  var myFactorial = 1;
  while (i <= num) {
    myFactorial *= i;
    i++;
  }
  return myFactorial;
}

```
