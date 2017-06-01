# Project Shift Coding Challenge

First of all, this isn't a pass/fail challenge - get as far as you can. Some may find this difficult and others may find it rudimentary given that it is very basic JavaScript. Either way it will give us great topic for conversation during the interview. We don't expect candidates to already know how to code, but we are interested to see what (if any) previous experience you have.

You can bring the answers with you to the interview, or submit them to aaron@projectshift.io.

## Problem 1
Write a function, that when invoked, alerts "Durham is awesome!"

## Problem 2
Write some JavaScript that loops through the following `bands` array and alerts, "I love [bandName]", obviously with the current band name string replacing the [bandName].

```JavaScript
var bands = ['Kiss', 'Aerosmith', 'ACDC', 'Led Zeppelin', 'Nickelback'];
```

## Problem 3
In the above challenge, when the loop gets to `'Nickelback'`, alert, "I DON'T love Nickelback!", but still alert the previous message for all other bands.

## Problem 4
Write some JavaScript that finds the average of the following array:

```JavaScript
var array = [34, 203, 16, 46, 34, 432, 342, 124, 33, 188, 12];
```

## Problem 5 (advanced)
Imagine that you're wanting to withdraw cash from the bank to cover specific costs. You want to withdraw the exact dollar amount, using the largest bills possible. For example, if the cost you were trying to cover is $1,745, you would need to withdraw 17 $100 bills, 2 $20 bills and 1 $5 bill. We'll leave change out of it for the sake of the exercise.

To solve this, write a function that takes one argument, `cost` and returns an object with the bill breakdown. For example, an the object returned for $1,745, would like this:

```JavaScript
{
  100: 17,
  20: 2,
  5: 1
}
```
