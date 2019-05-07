# Roman Numerals

Taken from [here](http://codingdojo.org/kata/RomanNumerals/) and [here](https://www.codewars.com/kata/roman-numerals-encoder).

## Description

The Romans wrote numbers using letters : I, V, X, L, C, D, M. Modern Roman numerals are written by expressing each digit separately starting with the left most digit and skipping any digit with a value of zero. In Roman numerals 1990 is rendered: 1000=M, 900=CM, 90=XC; resulting in MCMXC. 2008 is written as 2000=MM, 8=VIII; or MMVIII. 1666 uses each Roman symbol in descending order: MDCLXVI.


### Part I
You should write a function to convert from normal numbers to Roman Numerals: eg
```
1 --> I
10 --> X
7 --> VII
2008 --> MDCLXVI
```

For a full description of how it works, take a look at [this website](http://www.novaroma.org/via_romana/numbers.html). Alternatively, the table below should give you some guidance.

```
Symbol    Value
I          1
V          5
X          10
L          50
C          100
D          500
M          1,000
```

There is no need to be able to convert numbers larger than about 3000. (The Romans themselves didn’t tend to go any higher).

### Part II

Write a function to convert in the other direction, ie numeral to digit.
