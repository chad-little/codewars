### [Problem](https://www.codewars.com/kata/523b4ff7adca849afe000035/javascript)

Make a simple function called greet that returns the most-famous "hello world!".

#### Style Points:

Sure, this is about as easy as it gets. But how clever can you be to create the  
most creative hello world you can think of? What is a "hello world" solution  
you would want to show your friends?

```
summation(2) -> 3
1 + 2

summation(8) -> 36
1 + 2 + 3 + 4 + 5 + 6 + 7 + 8
```

```javascript
var summation = function (num) {
  // Code here
};
// Sample Test:
describe("summation", function () {
  it("should return the correct total", function () {
    Test.assertEquals(summation(1), 1);
    Test.assertEquals(summation(8), 36);
  });
});
```

### [Solution](https://www.codewars.com/kata/523b4ff7adca849afe000035/solutions/javascript)

```javascript
function greet() {
  return "hello world!";
}
```
