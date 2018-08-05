# JavaScript Parttens 

## JavaScript: Concept

### Object-Oriented

Only five primitive types (not objects) : number, string, boolean, null, and undefined. 

primitive wrappers: number, string, boolean

**Object**: 

key-value pairs : properties can be functions (method)

can be modified at any time. 

objects: Native [built-in | user-defined]   |    Host [DOM]

### No Classes

### Prototype

prototype is an object and every function has a prototype property.

### Environment

evironment provide their own host object

## ECMAScript 5

JavaScript (DOM, BOM, and extra host objects) is based on ES.

strict mode

## The Console

Safari and Chrome | WebKit browser

console is part of the environmet and is presented in most current browser.







## Essentials

### Minimizing Globals

#### The Problem with Globals

can use variables without declaring them | implied globals 

eg. var a, b = 0; result = a + b; | var a = b =0;

#### Side Effects When Forgetting var

Globals created with var cannot be deleted; Implied globals can be deleted.

#### Access to the Global Object

#### Single var Pattern

#### Hoisting: A Problem with Scattered vars



### for Loops

~~~javascript
var i, myarray = [];
for (i = myarray.length; i--;){
    //do something
}
~~~

### for-in Loops 

= enumeration    

use normal for loops with arrarys and for-in loops for objects









