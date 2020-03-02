---
title: "Methods of Primitives — Strings"
description: "In this article brief about the Strings methods."
date: "2020-03-01T15:41:01.663Z"
categories: []
published: true
canonical_link: https://medium.com/@197akshaytitar/methods-of-primitives-strings-ab2f845f09f
redirect_from:
  - /methods-of-primitives-strings-ab2f845f09f
---

#### what are methods of primitives?

JavaScript allows us to work with primitives (strings, numbers, etc.) as if they were objects. They also provide methods to call as such.

There are mainly two types of methods :

-   String methods
-   Array methods

#### String -methods -:

The string object lets you work with a series of characters; it wraps Javascript’s string primitive data type with a number of helper methods.

As JavaScript automatically converts between string primitives and String objects, you can call any of the helper methods of the String object on a string primitive.

#### Basic Concept of String Methods -:

-   Syntax — String(thing)

String — A string is a variable where we store value

thing- Anything to be converted to a string.

---

There are many types of String methods we will see one method with an example.

```
let string ="Akshay"
```

here we declare a variable string with a value of “Akshay”.

now we apply string methods on this string one by one -:

-   String.length -:

```
string.length;

6
```

here we use the length method to calculate the length of a string.

which returns a value of 6.

-   String.repeat() -:

```
string.repeat(2);

"AkshayAkshay"
```

In this method, It repeats the string with its given parameter, which declares inside ().

#### [includes startsWith, endsWith](https://javascript.info/string#includes-startswith-endswith)

The more modern method [str.includes(substring, pos)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/includes) returns true/false depending on whether a string contains substring within.

It’s the right choice if we need to test for the match, but don’t need its position:

```
alert( "Widget with id".includes("Widget") ); // true

alert( "Hello".includes("Bye") ); // false
```

The optional second argument of sting.includes is the position to start searching from:

```
alert( "Widget".includes("id") ); // true
alert( "Widget".includes("id", 3) ); // false, from position 3 there is no "id"
```

The methods [string.startsWith](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/startsWith) and [string.endsWith](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/endsWith) do exactly what they say:

```
alert( "Widget".startsWith("Wid") ); // true, "Widget" starts with "Wid"
alert( "Widget".endsWith("get") ); // true, "Widget" ends with "get"
```

In this link, we can study more about string and string- methods

[**String**  
_The String global object is a constructor for strings or a sequence of characters. String literals take the forms…_developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String# "https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String#")[](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String#)
