## Return Negative

```js
function makeNegative(number) {
    if (number > 0) {
        return -number;
    }
    
    return number;
}
```

## Sum of Positive

```js
function positiveSum(numbers){
  let positiveSum = 0;
  for(i = 0; i < numbers.length; i++){
    if (numbers[i] > 0){
      positiveSum += numbers[i];
   }
 }
 
return positiveSum;
}

const numbers = [1, 2, 3, 4, 5];

console.log(positiveSum(numbers));
```

## Function 2

```js
function square(num){
  return num * num;
}

console.log(square(5));
```

## Sum Arrays

```js
// Sum Numbers
function sum(numbers) {
  let sum = 0;
  if (numbers.length === 0){
    return 0;
    for (let i = 0; i < numbers.length; i++){
    sum += numbers[i];
    }
  }
  return sum;
}

const numbers = [1, 5.2, 4, 0, -1];

console.log(sum(numbers));
```

## Reversed Strings

```js
function solution(str){
    let solutionStr = "";
    for (i = str.length - 1; i >= 0; i--) {
      solutionStr += str[i];
    }
    return solutionStr;
  }
  
  console.log(solution("world"));
  console.log(solution("word"));
```
