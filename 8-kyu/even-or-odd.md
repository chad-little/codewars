### [Problem](https://www.codewars.com/kata/53da3dbb4a5168369a0000fe/javascript)

Create a function (or write a script in Shell) that takes an integer as an  
argument and returns "Even" for even numbers or "Odd" for odd numbers.

```javascript
function even_or_odd(number) {
  // ...
}
// Sample Test:
Test.assertEquals(even_or_odd(2), "Even");
Test.assertEquals(even_or_odd(0), "Even");
Test.assertEquals(even_or_odd(7), "Odd");
Test.assertEquals(even_or_odd(1), "Odd");
```

### [Solution](https://www.codewars.com/kata/53da3dbb4a5168369a0000fe/solutions/javascript)

```javascript
function even_or_odd(number) {
  if (number % 2 === 0) {
    return "Even";
  } else {
    return "Odd";
  }
}
```
