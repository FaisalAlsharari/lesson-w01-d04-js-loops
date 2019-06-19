

# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

```
var printNumber= 0;
while ( printNumber < 10){
console.log(printNumber);
printNumber = printNumber +1;
}
```

<br>

## Print every number from 10 to 0

```
var printNumber= 10;
while ( printNumber >=0){
console.log(printNumber);
printNumber = printNumber -1;
}
```

<br>

## Print every number from 4 to -16

```
var printNumber= 4;
while ( printNumber >=-16){
console.log(printNumber);
printNumber = printNumber -1;
}
```

<br>

## Print every fifth number from 8 to 41

```
var printEveryFifthNumbe= 8;
while ( printEveryFifthNumbe <=48){
console.log(printEveryFifthNumbe);
printEveryFifthNumbe = printEveryFifthNumbe +5;
}
```

<br>

## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"


```
let Fizzbuzz = 1;
while( Fizzbuzz <=100){
if ( Fizzbuzz % 3==0) 
console.log(Fizzbuzz+' Fizz');     
if ( Fizzbuzz % 5==0)
console.log(Fizzbuzz+' Buzz');
if ((Fizzbuzz %3 ==0) && (Fizzbuzz%5==0))
console.log(Fizzbuzz +' Fizzbuzz');
Fizzbuzz ++;
}
```

<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```
for ( let i=0; i<=20; i++){
if( i % 2==0)
console.log(i + ' even');
else
console.log(i + ' odd');
}
```

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


```
for (let N=0; N<=10; N++){

console.log( N +' * 9 = ' +N*9 );
}
```

<br>

## The Grade Assigner

Check the results for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

```
for (let i = 60; i<=100; i++){
    if (i >= 80 && i<90)
    console.log("For "+i+" you got a B.");
    if (i >= 90 && i<=100)
    console.log("For "+i+" you got an A.");
    if ( i >=70 && i<80)
    console.log("For "+i+" you got a D.");
}
```
