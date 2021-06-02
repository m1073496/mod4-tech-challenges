# Problem - Next Palindrome
Any number that reads the same way forwards as it does backwards is a palindrome. For instance, `12321` would be considered a palindrome, whereas `123` would not be. 

Write a function that takes in an integer and returns the next palindrome. For instance:

```js
findNextPalindrome(100)
// should return 101
```

and 

```js
findNextPalindrome(101)
// should return 111
```

# Instructions

1. Copy this markdown and paste in your own, private gist
2. In your private gist, fill out the questions below
4. Submit by the due time as instructed in Zoom


## Rewrite the question in your own words:

Write a function that takes in an integer
Find the next integer that counts as a palindrome
Return that integer



## What assumptions will you make about this problem if you cannot ask any more clarifying questions? What are your reasons for making those assumptions?

The function will only take in integers (if this is not the case, set up a conditional that will handle arguments that are non-integers)
If the argument passed in is itself a palindrome, the function will not return this argument but will instead find the next one


## What are your initial thoughts about this problem? (high level design, 2-3 sentences)

I need to have some sort of counter that starts at the argument +1
At each stage of the counter, I need to break the integers into separate items, reverse them and compare to original version
If identical, return that integer


## How would you identify the elements of this problem?

- [ ] Searching of Data
- [ x ] Sorting of Data
- [ ] Pattern Recognition
- [ ] Build/Navigate a Grid
- [ ] Math
- [ ] Language API knowledge
- [ ] Optimization


## Which data structure(s) do you think you'll use? What pros/cons do you see with that choice?

I don't know what this means 😎


## Write out a few lines of initial pseudocode: (mid-level design, NOT REAL CODE)

I need to have some sort of counter that starts at the argument +1
At each stage of the counter, I need to break the integers into separate items, reverse them and compare to original version
If identical, return that integer

## Write out any implementation code OR link to repl
https://replit.com/@m1073496/techChallenge#index.js

## What is the Big O complexity of your solution?
