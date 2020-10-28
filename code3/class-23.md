# Reading notes
## Concepts of Functional Programming in Javascript
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data —. 
* Pure functions benefits: the code will be easier to test. 
### Immutability
tate cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value
### Referential transparency
This pure function will always have the same output, given the same input.if a function consistently yields the same result for the same input, it is referentially transparent.
**"pure functions + immutable data = referential transparency"*

## Refactoring JavaScript for Performance and Readability 
There's a middle ground between speed and comprehension and that's where good code lives. Examples:
*  form of hash function, which Maps and Sets use under the surface. A hash function is used to map a given key to a location in the hash table. Below, this happens when we place our short URL into the store in makeShort and when we get it back out in getLong. Depending on how you're measuring run time, the result is that on average we only need to check one bucket 

* separated some logic and reduced the number of lines of code. We inlined a function called pick that accepts an array of length 1 and up and returns a random choice, then we used a template literal to build an URL.
