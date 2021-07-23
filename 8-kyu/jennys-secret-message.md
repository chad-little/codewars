### [Problem](https://www.codewars.com/kata/55225023e1be1ec8bc000390/javascript)

Jenny has written a function that returns a greeting for a user. However,  
she's in love with Johnny, and would like to greet him slightly different.  
She added a special case to her function, but she made a mistake.

Can you help her?

```javascript
function greet(name) {
  return "Hello, " + name + "!";
  if (name === "Johnny") return "Hello, my love!";
}
// Sample Test:
describe("Jenny's greeting function", function () {
  it("should greet some people normally", function () {
    Test.assertEquals(greet("Jim"), "Hello, Jim!");
    Test.assertEquals(greet("Jane"), "Hello, Jane!");
    Test.assertEquals(greet("Simon"), "Hello, Simon!");
  });
  it("should greet Johnny a little bit more special", function () {
    Test.assertEquals(greet("Johnny"), "Hello, my love!");
  });
});
```

### [Solution](https://www.codewars.com/kata/55225023e1be1ec8bc000390/solutions/javascript)

```javascript
function greet(name) {
  return name === "Johnny" ? "Hello, my love!" : `Hello, ${name}!`;
}
```
