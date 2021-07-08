### [Problem](https://www.codewars.com/kata/576bb71bbbcf0951d5000044/javascript)

Given an array of integers.

Return an array, where the first element is the count of positives numbers and  
the second element is sum of negative numbers.

If the input array is empty or null, return an empty array.

#### Example:

For input `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10, -11, -12, -13, -14, -15]`, you  
should return `[10, -65]`.

```javascript
function countPositivesSumNegatives(input) {
    return ?;
}
// Sample Test:
describe("Example tests", function(){
    var testData = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, -11, -12, -13, -14, -15];
    var actual = countPositivesSumNegatives(testData);
    var expected = [10, -65];

    Test.expect(actual[0] == expected[0] && actual[1] == expected[1], "Wrong return value.");

    testData = [0, 2, 3, 0, 5, 6, 7, 8, 9, 10, -11, -12, -13, -14];
    actual = countPositivesSumNegatives(testData);
    expected = [8, -50];

    Test.expect(actual[0] == expected[0] && actual[1] == expected[1], "Wrong return value.");
});
```

### [Solution](https://www.codewars.com/kata/576bb71bbbcf0951d5000044/solutions/javascript)

```javascript
function countPositivesSumNegatives(input) {
  if (!input || input.length === 0) return [];
  let arr = [0, 0];
  for (let i = 0; i < input.length; i++) {
    if (input[i] > 0) {
      arr[0]++;
    } else {
      arr[1] += input[i];
    }
  }
  return arr;
}
```
