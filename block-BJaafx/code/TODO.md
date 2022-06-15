1. Using loops take 10 inputs from user and find the average of all the numbers.
   function averageCalculator (numvalues) {
  var result1 = 0;
   for(i=0; i < numvalues; i++) {    
    var score = +prompt("input the score");   
    result1 += score;    
}
alert(result1 / numvalues);
}


2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```
...println is not defined

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

function getEvenSum(max){
  return max*(max+1)
}
getEvenSum(10)

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
function getOddSum(max){
  return max**2
}
getOddSum(10)

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.
 
 function getProductOfDigits(num){
   product=1;
   if(num>0){
     r=num%10;
     num=num-r
     product=r*product;
     num=num/10;
   }
   return product;
 }

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // output..
..Bigger than 5.
check(1); // output..
...Smaller than 5.
check(5); // output.
....5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // what will be the output
  Who are you
getOutput('John'); // what will be the output
Who are you
getOutput(); // what will be the output
Who are you.
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output
Who are you
getOutput('John'); // what will be the output
Who are you

getOutput(); // what will be the output
Who are you

```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
  yes,function can have multiple statement.
10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
"In 'for' loop the initialization once done is never repeated. In while loop if initialization is done during condition checking, then initialization is done each time the loop iterate".
