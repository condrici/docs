# PHP

The purpose of this document is to provide a nice overview of the PHP language where I can always refer to, should I want to make sure that my knowledge is up to date.

url: https://www.php.net/manual/en/langref.php

### Types
- booleans
- integers
- floating point numbers
- strings
- arrays
- iterables
- objects
- resources
- null
- Callbacks \ Callables
- Pseudo-types and variables
- Type juggling

### Variables
- predefined variables
- variable scope
- variable variables
- variables from external sources

### Constants
- overview
- magic constants

### Operators
- operator precedence
- arithmetic operators
- assignment operators
- bitwise operators
- comparison operators
- error control operators
- execution operators
- incrementing/decrementing operators
- logical operators
- string operators
- array operators
- type operators

### Control Structures
- if
- else
- else/ else if
- while
- do-while
- for
- foreach
- break
- continue
- switch
- declare
- return
- require
- include
- require_once
- include_once
- goto

### Functions
- User-defined functions
- Function arguments
- Returning values
- Variable functions
- Built-in functions
- Anonymous functions

### Classes and objects

- Properties
- Class Constants
- Autoloading Classes
- Constructors and Destructors
- Visibility
- Object Inheritance
- Scope Resolution Operator (::)
- Static Keyword
- Class Abstraction
- Object Interfaces
- Traits
- Anonymous classes
- Overloading
- Object Iteration
- Magic Methods
- Final Keyword
- Object Cloning
- Comparing Objects
- Type Hinting
- Late Static Bindings
- Objects and references
- Object Serialization
- OOP Changelog

### Namespaces

- Defining namespaces
- Declaring sub-namespaces
- Defining multiple namespaces in the same file
- Namespaces and dynamic language features
- Namespace keyword and __NAMESPACE__ constant
- Using namespaces: Aliasing/Importing
- Global space
- Using namespaces: fallback to global function/constant
- Name resolution rules

### Errors

### Exceptions

### Generators

### References
- passing by reference
- returning references
- unsetting references
- spotting references

### Predefined Exceptions
- Exception
- ErrorException
- Error
- ArgumentCountError
- ArithmeticError
- AssertionError
- DivisionByZeroError
- CompileError
- ParseError
- TypeError

### Predefined Interfaces and Classes
- Traversable — The Traversable interface
- Iterator — The Iterator interface
- IteratorAggregate — The IteratorAggregate interface
- Throwable
- ArrayAccess — The ArrayAccess interface
- Serializable — The Serializable interface
- Closure — The Closure class
- Generator — The Generator class
- WeakReference — The WeakReference class

### Context options and parameters
- Socket context options — Socket context option listing
- HTTP context options — HTTP context option listing
- FTP context options — FTP context option listing
- SSL context options — SSL context option listing
- CURL context options — CURL context option listing
- Phar context options — Phar context option listing
- MongoDB context options — MongoDB context option listing
- Context parameters — Context parameter listing
- Zip context options — Zip context option listing

### Protocols and wrappers
- file:// — Accessing local filesystem
- http:// — Accessing HTTP(s) URLs
- ftp:// — Accessing FTP(s) URLs
- php:// — Accessing various I/O streams
- zlib:// — Compression Streams
- data:// — Data (RFC 2397)
- glob:// — Find pathnames matching pattern
- phar:// — PHP Archive
- ssh2:// — Secure Shell 2
- rar:// — RAR
- ogg:// — Audio streams
- expect:// — Process Interaction Streams

### Array functions
- array_change_key_case
- array_chunk
- array_column
- array_combine
- array_count_values

- array_diff Compares two arrays, only values
- array_diff_key, Compares two arrays, only keys
- array_diff_ukey, Compares two arrays, only keys via user defined func
- array_diff_assoc, Compares two arrays, both keys and values
- array_diff_uassoc, Compares two arrays, both keys and values via user defined func

- array_udiff
- array_udiff_assoc
- array_udiff_uassoc

- array_fill
- array_fill_keys

- array_filter
- array_flip

- array_intersect
- array_intersect_key
- array_intersect_ukey
- array_intersect_assoc
- array_intersect_uassoc

- array_uintersect
- array_uintersect_assoc
- array_uintersect_uassoc

- array_keys
- array_key_exists
- array_key_first
- array_key_last

- array_map

- array_merge
- array_merge_recursive

- array

- compact
- count
- extract
- in_array
- key_exists
- key
- list
- shufle
- sizeof

- current
- pos
- next
- prev
- end

- array_pad
- array_pop
- array_product
- array_push
- array_rand
- array_reduce

- array_replace
- array_replace_recursive

- array_reverse
- array_search
- array_shift
- array_slice
- array_splice
- array_sum
- array_unique
- array_unshift
- array_values

- array_walk
- array_walk_recursive

- sort
- rsort
- ksort
- krsort
- natsort
- natcasesort
- usort
- uasort
- uksort
- asort
- arsort
- array_multisort
