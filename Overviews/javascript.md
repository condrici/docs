# Javascript

Quick reference for Javascript.

##  Built-in Objects

* Array
* ArrayBuffer
* AsyncFunction
* Atomics
* BigInt
* Boolean
* DataView
* Date
* Error
* EvalError
* Float32Array
* Float64Array
* Function
* Generator
* GeneratorFunction
* Infinity
* Int16Array
* vInt32Array
* Int8Array
* InternalError
* Intl
* Intl.Collator
* Intl.DateTimeFormat
* Intl.ListFormat
* Intl.NumberFormat
* Intl.PluralRules
* Intl.RelativeTimeFormat
* JSON
* Map
* Math
* NaN
* Number
* Object
* Promise
* Proxy
* RangeError
* ReferenceError
* Reflect
* RegExp
* Set
* SharedArrayBuffer
* String
* Symbol
* SyntaxError
* TypeError
* TypedArray
* URIError
* Uint16Array
* Uint32Array
* Uint8Array
* Uint8ClampedArray
* WeakMap
* WeakSet
* WebAssembly
* decodeURI()
* decodeURIComponent()
* encodeURI()
* encodeURIComponent()
* escape()
* eval()
* isFinite()
* isNaN()
* null
* parseFloat()
* parseInt()
* undefined
* unescape()
* uneval()

## Expressions and operators

* Arithmetic operators
* Array comprehensions
* Assignment operators
* Bitwise operators
* Comma operator
* Comparison operators
* Conditional (ternary) operator
* Destructuring assignment
* Expression closures
* Generator comprehensions
* Grouping operator
* Legacy generator function expression
* Logical operators
* Object initializer
* Operator precedence
* Pipeline operator
* Property accessors
* Spread syntax
* async function expression
* await
* class expression
* delete operator
* function expression
* function* expression
* in operator
* instanceof
* new operator
* new.target
* super
* this
* typeof
* void operator
* yield

## Statements & declarations

* async function
* block
* break
* class
* const
* continue
* debugger
* default
* do...while
* empty
* export
* for
* for await...of
* for each...in
* for...in
* for...of
* function declaration
* function*
* if...else
* import
* import.meta
* label
* let
* return
* switch
* throw
* try...catch
* var
* while
* with

## Functions

* Arrow functions
* Default parameters
* Method definitions
* Rest parameters
* The arguments object
* getter
* setter

## Classes

constructor
extends
static

## Errors

## Misc

* JavaScript technologies overview
* Lexical grammar
* JavaScript data structures
* Enumerability and ownership of properties
* Iteration protocols
* Strict mode
* Transitioning to strict mode
* Template literals
* Deprecated features

## Array properties

* constructor	Returns the function that created the Array object's prototype
* length	Sets or returns the number of elements in an array
* prototype	Allows you to add properties and methods to an Array object

## Array Methods

* concat()	Joins two or more arrays, and returns a copy of the joined arrays
* copyWithin()	Copies array elements within the array, to and from specified positions
* entries()	Returns a key/value pair Array Iteration Object
* every()	Checks if every element in an array pass a test
* fill()	Fill the elements in an array with a static value
* filter()	Creates a new array with every element in an array that pass a test
* find()	Returns the value of the first element in an array that pass a test
* findIndex()	Returns the index of the first element in an array that pass a test
* forEach()	Calls a function for each array element
* from()	Creates an array from an object
* includes()	Check if an array contains the specified element
* indexOf()	Search the array for an element and returns its position
* isArray()	Checks whether an object is an array
* join()	Joins all elements of an array into a string
* keys()	Returns a Array Iteration Object, containing the keys of the original array
* lastIndexOf()	Search the array for an element, starting at the end, and returns its position
* map()	Creates a new array with the result of calling a function for each array element
* pop()	Removes the last element of an array, and returns that element
* push()	Adds new elements to the end of an array, and returns the new length
* reduce()	Reduce the values of an array to a single value (going left-to-right)
* reduceRight()	Reduce the values of an array to a single value (going right-to-left)
* vreverse()	Reverses the order of the elements in an array
* shift()	Removes the first element of an array, and returns that element
* slice()	Selects a part of an array, and returns the new array
* some()	Checks if any of the elements in an array pass a test
* sort()	Sorts the elements of an array
* splice()	Adds/Removes elements from an array
* toString()	Converts an array to a string, and returns the result
* unshift()	Adds new elements to the beginning of an array, and returns the new length
* valueOf()	Returns the primitive value of an array

## String properties

* constructor	Returns the string's constructor function
* length	Returns the length of a string
* prototype	Allows you to add properties and methods to an object

## String methods

* charAt()	Returns the character at the specified index (position)
* charCodeAt()	Returns the Unicode of the character at the specified index
* concat()	Joins two or more strings, and returns a new joined strings
* endsWith()	Checks whether a string ends with specified string/characters
* fromCharCode()	Converts Unicode values to characters
* includes()	Checks whether a string contains the specified string/characters
* indexOf()	Returns the position of the first found occurrence of a specified value in a string
* lastIndexOf()	Returns the position of the last found occurrence of a specified value in a string
* localeCompare()	Compares two strings in the current locale
* match()	Searches a string for a match against a regular expression, and returns the matches
* repeat()	Returns a new string with a specified number of copies of an existing string
* replace()	Searches a string for a specified value, or a regular expression, and returns a new string where the specified values are replaced
* search()	Searches a string for a specified value, or regular expression, and returns the position of the match
* slice()	Extracts a part of a string and returns a new string
* split()	Splits a string into an array of substrings
* startsWith()	Checks whether a string begins with specified characters
* substr()	Extracts the characters from a string, beginning at a specified start position, and through the specified number of character
*  toLocaleLowerCase()	Converts a string to lowercase letters, according to the host's locale
* toLocaleUpperCase()	Converts a string to uppercase letters, according to the host's locale
* toLowerCase()	Converts a string to lowercase letters
* toString()	Returns the value of a String object
* toUpperCase()	Converts a string to uppercase letters
* trim()	Removes whitespace from both ends of a string
* valueOf()	Returns the primitive value of a String object

## Global functions

* decodeURI()	Decodes a URI
* decodeURIComponent()	Decodes a URI component
* encodeURI()	Encodes a URI
* encodeURIComponent()	Encodes a URI component
* escape()	Deprecated in version 1.5. Use encodeURI() or encodeURIComponent() instead
* eval()	Evaluates a string and executes it as if it was script code
* isFinite()	Determines whether a value is a finite, legal number
* isNaN()	Determines whether a value is an illegal number
* Number()	Converts an object's value to a number
* parseFloat()	Parses a string and returns a floating point number
* parseInt()	Parses a string and returns an integer
* String()	Converts an object's value to a string
* unescape()	Deprecated in version 1.5. Use decodeURI() or decodeURIComponent() instead

## Global properties

* Infinity	A numeric value that represents positive/negative infinity
* NaN	"Not-a-Number" value
* undefined	Indicates that a variable has not been assigned a value



