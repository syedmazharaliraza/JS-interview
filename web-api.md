### This might be a heartbreak to a lot of Javascript developers out there, but the truth is...
The very first line of code you ran as a beginner JS developer, viz
```
console.log()
``` 
is not a part of the Javascript language. Confused? Let me explain.

The console object (whose log method is used to print data on the web console) is one of the **Web APIs** provided by the Browser to the JavaScript Engine, which means it is your browser that is providing this functionality that is in return implemented through Javascript.

All browsers have a *set of built-in Web APIs* to support complex operations, such as DOM, Fetch, History, Service Workers, and Web Storage APIs. Now you may wonder, what exactly is a part of Javascript then?

Well, the parts of Javascript that are standard across all environments are detailed in the ECMA Specs (primitives, data types, language grammar and syntax, arithmetic and logical operations, built-in objects and functions, etc.). This means that while ```Array.isArray()``` is built into JS, ```setTimeout()``` and ```console``` aren’t.
