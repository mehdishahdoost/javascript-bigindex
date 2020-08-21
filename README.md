# Javascript Big Index

#### Facts

- JavaScript accepts both double and single quotes.
- JavaScript was invented by Brendan Eich in 1995, and became an ECMA standard in 1997.
- ECMA-262 is the official name of the standard. ECMAScript is the official name of the language.
- In JavaScript, the window object is the global scope object, that means that variables, properties, and methods by
  default belong to the window object. This also means that specifying the window keyword is optional. (window.alert , windpw.print)
- Ending statements with semicolon is not required, but highly recommended.
- Hyphens are not allowed in JavaScript. They are reserved for subtractions. (ex: first-name)
- After the declaration, the variable has no value technically it has the value of undefined.
- If you re-declare a JavaScript variable, it will not lose its value. ex:

 <pre>
   <code>
    var name = "mehdi";
    var name;
    console.log(name); //result: mehdi
   </code>    
</pre>

- If you put a number in quotes, the rest of the numbers will be treated as strings, and concatenated.
<pre>
    <code>
        var = "1" + 2 + 3; // result: 123
    </code>
</pre>
- Since JavaScript treats a dollar sign as a letter, identifiers containing \$ are valid variable names
<pre>
<code>
    var $$$ = 2;
    var $=3;
    var $name=123;
    var name$family='mehdi';
</code>
</pre>

- typeof null is null (it maybe a bug)
- undefined and null are equal in value but different in tye
<pre>
<code>
    typeof undefined //result: undefined
    typeof null // result: null
    null == undefined // result true
    null === undefined // result false
</code>
</pre>

* Comparing two JavaScript objects will always return false.
* JavaScript Numbers are Always 64-bit Floating Point
* NaN is a number: typeof NaN returns number.
* Infinity is a number: typeof Infinity returns number.
* toFixed(2) is perfect for working with money.
* The valueOf() method is used internally in JavaScript to convert Number objects to primitive values.
* In JavaScript, arrays use numbered indexes.  
* In JavaScript, objects use named indexes.
* Arrays are a special kind of objects, with numbered indexes.
* There are generally 3 types of JavaScript date input formats:
<pre>
<code>
ISO Date	"2015-03-25" (The International Standard)
Short Date	"03/25/2015"
Long Date	"Mar 25 2015" or "25 Mar 2015"
</code>
</pre>  
The ISO format follows a strict standard in JavaScript. The other formats are not so well defined and might be browser specific.

### Functional Programming in JavaScript

#### what is functional programming?

* it's programming paradigm
* A coding style
* A mindset
### Functional programming features

* Do everything with functions
* Avoid side effect : use pure function
* Use Higher order functions : functions can be inputs/outputs
* Don't iterate: map, filter, reduce
* Avoid mutability: use immutable data
* Persisted Data structure  

  
  

  
