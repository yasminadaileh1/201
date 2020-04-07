# Refactoring

## Concepts of Functional Programming in Javascript

**Functional programming** is a paradigm style the structure of computer programs.

we have functional programming the first one is the *pure function*, It returns the same result if given the same arguments and It does not cause any observable side effects and the benefits of it is easier to test codes. The second one is the *Immutability* it is a function that Unchanging over time or unable to be changed. Third one is *referential transparency* it is a component of pure functions and immutable data. The fourth one is *Functions as first-class entities*, the idea of this function is functions are also treated as values and used as data, ant it can :

* refer to it from constants and variables
* pass it as a parameter to other functions
* return it as result from other functions

And we have *Higher-order functions*, it is either takes one or more functions as arguments, or returns a function as its result. *Filter* function given a collection, we want to filter by an attribute. The filter function expects a true or false value to determine if the element should or should not be included in the result collection.
The *map* method transforms a collection by applying a function to all of its elements and building a new collection from the returned values.
About the *Reduce* The idea of reduce is to receive a function and a collection, and return a value created by combining the items.

## Refactoring JavaScript for Performance and Readability

**Strategies**:
Here are some straightforward to implement methods that can lead to easier to read code. There are no absolutes when it comes to clean code — there's always an edge case!

1. Return early from functions:
2. Cache variables so functions can be read like sentences
3. Check for Web APIs before implementing your own functionality

