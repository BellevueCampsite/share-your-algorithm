# [Check for Palindromes](http://www.freecodecamp.com/challenges/check-for-palindromes)

*Return true if the given string is a palindrome. Otherwise, return false.*

## Solutions

```javascript
function palindrome(str) {
  var myStr = str.toLowerCase().replace(/[^a-z0-9]/gi, '');
  var myStrReversed = myStr.split('').reverse().join('');
  return myStr === myStrReversed;
}

```
