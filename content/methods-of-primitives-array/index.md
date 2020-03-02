---
title: "Methods of Primitives — Array"
description: "In this article brief about the Strings methods."
date: "2020-03-02T04:05:44.539Z"
categories: []
published: true
canonical_link: https://medium.com/@197akshaytitar/methods-of-primitives-array-fe4ca715b5e5
redirect_from:
  - /methods-of-primitives-array-fe4ca715b5e5
---

#### what are methods of primitives?

JavaScript allows us to work with primitives (strings, numbers, etc.) as if they were objects. They also provide methods to call as such.

There are mainly two types of methods :

-   String methods
-   Array methods

#### Array-Methods-:

Arrays are list-like objects whose prototype has methods to perform traversal and mutation operations. Neither the length of a JavaScript array nor the types of its elements are fixed.

#### Basic Concept of Array Methods -:

-   Syntax — Array\[\];

Array — In the array, you can store collection values.

\[\]-Array having predefined index number, with this syntax we can call that index value.

---

There are many types of Array methods we will see one method with an example.

```
let arr=[1,2,3,4,5,6]
```

here we declare an array with arr variable with a collection of values(numbers).

-   Array.length -:

```
arr.length;
6;
```

here we use the length method to calculate the length of an array.

which returns a value of 6,

which is the length means the total number of values stores in an array.

-   Array.indexof _-:_

```
arr.indexof(1);
0;
```

In this method, we get to know the index number of value which stores in the array.

#### Transform Of Array -:

In this type of array methods, we can transform and reorder an array.

-   `map(func)` – creates a new array from the results of calling `func` for every element.
-   `sort(func)` – sorts the array in-place then returns it.
-   `reduce(func, initial)` – calculate a single value over the array by calling `func` for each element and passing an intermediate result between the calls.

#### [Add/remove items](https://javascript.info/array-methods#add-remove-items)

These are some basic methods of an array.

-   `arr.push(...items)` – adds items to the end,
-   `arr.pop()` – extracts an item from the end,
-   `arr.shift()` – extracts an item from the beginning,
-   `arr.unshift(...items)` – adds items to the beginning.

In this link, we can study more about string and Array- methods

[**Array**  
_The JavaScript Array class is a global object that is used in the construction of arrays; which are high-level…_developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array "https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array")[](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
