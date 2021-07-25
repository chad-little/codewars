### [Problem](https://www.codewars.com/kata/57a429e253ba3381850000fb/javascript)

Write function bmi that calculates body mass index (bmi = weight / height2).

if bmi <= 18.5 return "Underweight"

if bmi <= 25.0 return "Normal"

if bmi <= 30.0 return "Overweight"

if bmi > 30 return "Obese"

```javascript
function bmi(weight, height) {
  return "";
}
// Sample Test:
describe("Tests", () => {
  it("test", () => {
    Test.assertEquals(bmi(80, 1.8), "Normal");
  });
});
```

### [Solution](https://www.codewars.com/kata/57a429e253ba3381850000fb/solutions/javascript)

```javascript
function bmi(weight, height) {
  const bmi = weight / height ** 2;
  if (bmi <= 18.5) return "Underweight";
  if (bmi <= 25) return "Normal";
  if (bmi <= 30) return "Overweight";
  return "Obese";
}
```
