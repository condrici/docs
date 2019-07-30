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
- array Create an array
- 
- array_change_key_case
- array_chunk
- array_column
- array_combine
- array_count_values
- 
- array_diff Compares two arrays, only values
- array_diff_key, Compares two arrays, only keys
- array_diff_ukey, Compares two arrays, only keys via user defined func
- array_diff_assoc, Compares two arrays, both keys and values
- array_diff_uassoc, Compares two arrays, both keys and values via user defined func
- 
- array_udiff
- array_udiff_assoc
- array_udiff_uassoc
- 
- array_intersect
- array_intersect_key
- array_intersect_ukey
- array_intersect_assoc
- array_intersect_uassoc
- 
- array_uintersect
- array_uintersect_assoc
- array_uintersect_uassoc
- 
- array_fill
- array_fill_keys
- 
- array_filter
- array_flip
- 
- array_keys
- array_key_exists
- array_key_first Gets the first key of an array (PHP 7.3+)
- array_key_last Gets the last key of an array (PHP 7.3+)
- 
- array_map
- 
- array_merge
- array_merge_recursive
- 
- compact
- list
- 
- count
- extract
- in_array
- key_exists
- key
- shufle
- sizeof
- 
- current
- pos
- next
- prev
- end
- reset
- 
- array_pad
- array_pop
- array_product
- array_push
- array_rand
- array_reduce
- 
- array_replace
- array_replace_recursive
- 
- array_reverse
- array_search
- array_shift
- array_slice
- array_splice
- array_sum
- array_unique
- array_unshift
- array_values
- 
- array_walk
- array_walk_recursive
- 
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

## Function functions

- call_user_func
- call_user_func_array
- forward_static_call
- forward_static_call_array
- func_get_arg
- func_get_args
- func_num_args
- function_exists
- get_defined_functions
- register_shutdown_functions
- register_tick_function
- unregister_tick_function

## Object functions

- autoload
- class_alias
- get_called_class
- get_class_methods
- get_class_vars
- get_class
- get_declared_classes
- get_declared_interfaces
- get_declared_traits
- get_object_vars
- get_parent_class
- interface_exists
- is_a
- is_subclass_of
- method_exists
- property_exists
- trait_exists

## Misc functions
- connection_aborted
- connection_status
- constant
- define
- defined
- die
- eval
- exit
- get_browser
- highlight_file
- highlight_string
- hrtime
- ignore_user_abort
- pack
- php_check_syntax
- php_strip_whitespace
- sapi_windows_cp_conv
- sapi_windows_cp_get
- sapi_windows_cp_is_utf8
- sapi_windows_cp_set
- sapi_windows_vt100_support
- show_source
- sleep
- sys_getloadavg
- time_nanosleep
- time_sleep_until
- uniqid
- unpack
- usleep

## Official Documentation
- Language Reference https://www.php.net/manual/en/langref.php
- Functions https://www.php.net/manual/en/funcref.php
- Features https://www.php.net/manual/en/features.php
- Core https://www.php.net/manual/en/internals2.php
- Appendices https://www.php.net/manual/en/appendices.php
