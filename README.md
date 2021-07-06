![](codewars.png)

# Ильинский Евгений
## Uplab Практика
____
# Задание 1 - Complementary DNA
Deoxyribonucleic acid (DNA) is a chemical found in the nucleus of cells and carries the "instructions" for the development and functioning of living organisms.
In DNA strings, symbols "A" and "T" are complements of each other, as "C" and "G". You have function with one side of the DNA (string, except for Haskell); you need to get the other complementary side. DNA strand is never empty or there is no DNA at all (again, except for Haskell).
# Выполнение:
```html
function DNAStrand(dna){
  var string = "" ;
  for(var i = 0 ; i < dna.length ; i++)
  {
  if(dna.charAt(i) == "A")
    string += "T"
  if(dna.charAt(i) == "T")
  string += "A"
  if(dna.charAt(i) == "C")
    string += "G"
  if(dna.charAt(i) == "G")
   string += "C"
  }
  return string 
}
```
____
# Задание 2 - Reverse words
Complete the function that accepts a string parameter, and reverses each word in the string. All spaces in the string should be retained.
# Выполнение:
```html
function reverseWords(str) {
return str.split("").reverse().join("").split(" ").reverse().join(" ")
}
```
____
# Задание 3 - Grasshopper - Summation
Write a program that finds the summation of every number from 1 to num. The number will always be a positive integer greater than 0.
# Выполнение:
```html
var summation = function (num) {
  let sum = 0;
  for (let i = 1; i <= num; i++) {
    sum += i;
  }
  return sum;
}
```
____
# Задание 4 - Beginner - Lost Without a Map
Given an array of integers, return a new array with each value doubled.
# Выполнение:
```html
function maps(x){
x2 = x.map(x => x * 2);
  return x2
}
```
____
# Задание 5 - Counting sheep...
Consider an array/list of sheep where some sheep may be missing from their place. We need a function that counts the number of sheep present in the array (true means present).
# Выполнение:
```html
function countSheeps(arrayOfSheep) {
  var count = 0;
for (let value of arrayOfSheep)
if (value)
count++;
return count;
  console.log(countSheeps(arrayOfSheep));
}
```
____
# Задание 6 - Even or Odd
Create a function (or write a script in Shell) that takes an integer as an argument and returns "Even" for even numbers or "Odd" for odd numbers.
# Выполнение:
```html
function even_or_odd(number) {
if(number % 2 == 0)
{
return "Even";
}else
{
return "Odd";
}
}
```
____
# Задание 7 - Sum of positive
You get an array of numbers, return the sum of all of the positives ones.

Example [1,-4,7,12] => 1 + 7 + 12 = 20

Note: if there is nothing to sum, the sum is default to 0.
# Выполнение:
```html
function positiveSum(arr) {
  var result = 0;
for (let i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
        result += arr[i];
    }
}
  return result;
}
```
____
# Задание 8 - Remove First and Last Character
It's pretty straightforward. Your goal is to create a function that removes the first and last characters of a string. You're given one parameter, the original string. You don't have to worry with strings with less than two characters.
# Выполнение:
```html
function removeChar(str){
 return str.slice(1, -1)
}
```
____
# Задание 9 - Opposite number
Very simple, given a number, find its opposite.
# Выполнение:
```html
function opposite(number) {
  return(-number);
}
```
____
# Задание 10 - Remove String Spaces
Simple, remove the spaces from the string, then return the resultant string.
# Выполнение:
```html
function noSpace(x){
 return x.replace(/\s/g, '');
}
```
