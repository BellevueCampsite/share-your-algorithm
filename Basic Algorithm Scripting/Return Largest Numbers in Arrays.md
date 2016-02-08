# [Return Largest Numbers in Arrays](http://www.freecodecamp.com/challenges/return-largest-numbers-in-arrays)

*Return an array consisting of the largest number from each provided sub-array. For simplicity, the provided array will contain exactly 4 sub-arrays.*

## Solutions

```javascript
function largestOfFour(arr) {
  var largestNumArr = [];
  for (var i = 0; i < arr.length; i++) {
    arr[i].sort(function(num1, num2) {
      return num2 - num1;
    });
  largestNumArr.push(arr[i][0]);
  }
  return largestNumArr;
}

```
