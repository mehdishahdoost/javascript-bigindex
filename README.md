# Javascript Big Index

#### Facts

* JavaScript accepts both double and single quotes.
* JavaScript was invented by Brendan Eich in 1995, and became an ECMA standard in 1997.
* ECMA-262 is the official name of the standard. ECMAScript is the official name of the language.
* In JavaScript, the window object is the global scope object, that means that variables, properties, and methods by 
default belong to the window object. This also means that specifying the window keyword is optional. (window.alert , windpw.print)
* Ending statements with semicolon is not required, but highly recommended.
* Hyphens are not allowed in JavaScript. They are reserved for subtractions. (ex: first-name)
* After the declaration, the variable has no value technically it has the value of undefined.
* If you re-declare a JavaScript variable, it will not lose its value. ex:
 
 <pre>
   <code>
    var name = "mehdi";
    var name;
    console.log(name); //result: mehdi
   </code>    
</pre>

* If you put a number in quotes, the rest of the numbers will be treated as strings, and concatenated.
<pre>
    <code>
        var = "1" + 2 + 3; // result: 123
    </code>
</pre>  
* Since JavaScript treats a dollar sign as a letter, identifiers containing $ are valid variable names
<pre>
<code>
    var $$$ = 2;
    var $=3;
    var $name=123;
    var name$family='mehdi';
</code>
</pre>
  

  

  

  

  
