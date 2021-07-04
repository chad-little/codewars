### [Problem](https://www.codewars.com/kata/57eadb7ecd143f4c9c0000a3/javascript)

Write a function to convert a name into initials. This kata strictly takes two  
words with one space in between them.

The output should be two capital letters with a dot separating them.

It should look like this:

`Sam Harris` => `S.H`

`Patrick Feeney` => `P.F`

```javascript
function abbrevName(name) {
  // code away
}
// Sample Test:
describe("Tests", () => {
  it("test", () => {
    Test.assertEquals(abbrevName("Sam Harris"), "S.H");
    Test.assertEquals(abbrevName("Patrick Feenan"), "P.F");
    Test.assertEquals(abbrevName("Evan Cole"), "E.C");
    Test.assertEquals(abbrevName("P Favuzzi"), "P.F");
    Test.assertEquals(abbrevName("David Mendieta"), "D.M");
  });
});
```

### [Solution](https://www.codewars.com/kata/57eadb7ecd143f4c9c0000a3/solutions/javascript)

```javascript
function abbrevName(name) {
  return name
    .split(" ")
    .map((name) => name[0])
    .toUpperCase();
    .join(".")
}
```
