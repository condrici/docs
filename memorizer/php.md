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

## String functions

- addcslashes — Quote string with slashes in a C style
- addslashes — Quote string with slashes
- 
- bin2hex — Convert binary data into hexadecimal representation
- chr — Generate a single-byte string from a number
- chunk_split — Split a string into smaller chunks
- 
- convert_cyr_string — Convert from one Cyrillic character set to another
- convert_uudecode — Decode a uuencoded string
- convert_uuencode — Uuencode a string
- 
- implode — Join array elements with a string
- explode — Split a string by a string
- join — Pseudonim pentru implode
- 
- count_chars — Return information about characters used in a string
- get_html_translation_table — Returns the translation table used by htmlspecialchars and htmlentities
- 
- hebrev — Convert logical Hebrew text to visual text
- hebrevc — Convert logical Hebrew text to visual text with newline conversion
- hex2bin — Decodes a hexadecimally encoded binary string
- 
- html_entity_decode — Convert HTML entities to their corresponding characters
- htmlentities — Convert all applicable characters to HTML entities
- htmlspecialchars_decode — Convert special HTML entities back to characters
- htmlspecialchars — Convert special characters to HTML entities
- 
- levenshtein — Calculate Levenshtein distance between two strings
- localeconv — Get numeric formatting information
- 
- md5 — Calculate the md5 hash of a string
- md5_file — Calculates the md5 hash of a given file
- sha1 — Calculate the sha1 hash of a string
- sha1_file — Calculate the sha1 hash of a file
- crc32 — Calculates the crc32 polynomial of a string
- crypt — One-way string hashing
- 
- metaphone — Calculate the metaphone key of a string
- money_format — Formats a number as a currency string
- nl_langinfo — Query language and locale information
- nl2br — Inserts HTML line breaks before all newlines in a string
- number_format — Format a number with grouped thousands
- ord — Convert the first byte of a string to a value between 0 and 255
- parse_str — Parses the string into variables
- quoted_printable_decode — Convert a quoted-printable string to an 8 bit string
- quoted_printable_encode — Convert a 8 bit string to a quoted-printable string
- quotemeta — Quote meta characters
- setlocale — Set locale information
- similar_text — Calculate the similarity between two strings
- soundex — Calculate the soundex key of a string
- sscanf — Parses input from a string according to a format
- 
- str_getcsv — Parse a CSV string into an array
- str_ireplace — Case-insensitive version of str_replace
- str_pad — Pad a string to a certain length with another string
- str_repeat — Repeat a string
- str_replace — Replace all occurrences of the search string with the replacement string
- str_rot13 — Perform the rot13 transform on a string
- str_shuffle — Randomly shuffles a string
- str_split — Convert a string to an array
- str_word_count — Return information about words used in a string
- 
- strchr — Pseudonim pentru strstr
- strcspn — Find length of initial segment not matching mask
- strip_tags — Strip HTML and PHP tags from a string
- stripcslashes — Un-quote string quoted with addcslashes
- stripslashes — Un-quotes a quoted string
- stristr — Case-insensitive strstr
- strlen — Get string length
- 
- strcmp — Binary safe string comparison
- strcasecmp — Binary safe case-insensitive string comparison
- strncasecmp — Binary safe case-insensitive string comparison of the first n characters
- strncmp — Binary safe string comparison of the first n characters
- strnatcmp — String comparisons using a "natural order" algorithm
- strnatcasecmp — Case insensitive string comparisons using a "natural order" algorithm
- strcoll — Locale based string comparison
- 
- strpbrk — Search a string for any of a set of characters
- 
- strpos — Find the position of the first occurrence of a substring in a string
- stripos — Find the position of the first occurrence of a case-insensitive substring in a string
- strripos — Find the position of the last occurrence of a case-insensitive substring in a string
- strrpos — Find the position of the last occurrence of a substring in a string
- 
- strrchr — Find the last occurrence of a character in a string
- strrev — Reverse a string
- strspn — Finds the length of the initial segment of a string consisting entirely of characters contained within a given mask
- strstr — Find the first occurrence of a string
- strtok — Tokenize string
- 
- strtr — Translate characters or replace substrings
- substr_compare — Binary safe comparison of two strings from an offset, up to length characters
- substr_count — Count the number of substring occurrences
- substr_replace — Replace text within a portion of a string
- substr — Return part of a string
- 
- trim — Strip whitespace (or other characters) from the beginning and end of a string
- ltrim — Strip whitespace (or other characters) from the beginning of a string
- rtrim — Strip whitespace (or other characters) from the end of a string
- chop — Pseudonim pentru rtrim
- 
- strtolower — Make a string lowercase
- strtoupper — Make a string uppercase
- ucfirst — Make a string's first character uppercase
- lcfirst — Make a string's first character lowercase
- ucwords — Uppercase the first character of each word in a string
- 
- echo — Output one or more strings
- print — Output a string
- printf — Output a formatted string
- fprintf — Write a formatted string to a stream
- vfprintf — Write a formatted string to a stream
- vprintf — Output a formatted string
- vsprintf — Return a formatted string
- wordwrap — Wraps a string to a given number of characters
- sprintf — Return a formatted string

## Output Control functions

- flush — Flush system output buffer
- ob_clean — Clean (erase) the output buffer
- ob_end_clean — Clean (erase) the output buffer and turn off output buffering
- ob_end_flush — Flush (send) the output buffer and turn off output buffering
- ob_flush — Flush (send) the output buffer
- 
- ob_get_clean — Get current buffer contents and delete current output buffer
- ob_get_contents — Return the contents of the output buffer
- ob_get_flush — Flush the output buffer, return it as a string and turn off output buffering
- ob_get_length — Return the length of the output buffer
- ob_get_level — Return the nesting level of the output buffering mechanism
- ob_get_status — Get status of output buffers
- 
- ob_gzhandler — ob_start callback function to gzip output buffer
- ob_implicit_flush — Turn implicit flush on/off
- ob_list_handlers — List all output handlers in use
- ob_start — Turn on output buffering
- output_add_rewrite_var — Add URL rewriter values
- output_reset_rewrite_vars — Reset URL rewriter values

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

## Variable functions

- boolval — Get the boolean value of a variable
- debug_zval_dump — Dumps a string representation of an internal zend value to output
- doubleval — Pseudonim pentru floatval
- empty — Determină dacă o variabilă este vidă
- floatval — Obține valoarea float a unei variabile
- get_defined_vars — Întoarce un msiv cu toate variabilele definite
- get_resource_type — Întoarce tipul resursei
- gettype — Obține tipul unei variabile
- import_request_variables — Importă variabilele GET/POST/Cookie în circumstanța globală
- intval — Obține valoarea întreagă a unei variabile
- is_array — Determină dacă o variabilă este un array
- is_bool — Determină dacă o variablă este un boolean
- is_callable — Verifică dacă conținutul unei variabile poate fi apelat în calitate de funcție
- is_countable — Verify that the contents of a variable is a countable value
- is_double — Pseudonim pentru is_float
- is_float — Determină dacă tipul unei variabile este float
- is_int — Determină dacă tipul unei variabile este integer
- is_integer — Pseudonim pentru is_int
- is_iterable — Verify that the contents of a variable is an iterable value
- is_long — Pseudonim pentru is_int
- is_null — Determină dacă o variabilă este NULL
- is_numeric — Determină dacă o variabilă este un număr sau un string numeric
- is_object — Determină dacă o variabilă este un obiect
- is_real — Pseudonim pentru is_float
- is_resource — Determină dacă o variabilă este o resursă
- is_scalar — Determină dacă o variabilă este un scalar
- is_string — Determină dacă tipul variabilei este string
- isset — Determină dacă o variablă este stabilită și nu este NULL
- print_r — Afișează informație lizibilă de om despre o variabilă
- serialize — Generează o reprezentare ce poate fi stocată a unei valori
- settype — Stabilește tipul unei variabile
- strval — Obține valoarea string a unei variabile
- unserialize — Creează o valoare PHP dintr-o reprezentare stocată
- unset — Elimină o variabilă dată
- var_dump — Afișează informația despre o variabilă
- var_export — Afișează sau întoarce o reprezentare string, ce poate fi prelucrată, a unei variabile


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

## Standard PHP Library (SPL)

## Topics
- Design Patterns
- Architectural Patterns
- Performance Optimization

## Design Patterns

#### Creational
- Abstract Factory
- Builder
- Factory Method
- Multiton
- Pool
- Prototype
- Simple Factory
- Singleton
- Static Factory

#### Structural
- Adapter / Wrapper
- Bridge
- Composite
- Data Mapper
- Decorator
- Dependency Injection
- Facade
- Fluent Interface
- Flyweight
- Proxy
- Registry

#### Behavioral
- Chain Of Responsibilities
- Command
- Iterator
- Mediator
- Memento
- Null Object
- Observer
- Specification
- State
- Strategy
- Template Method
- Visitor

#### More
- Service Locator
- Repository
- Entity-Attribute-Value (EAV)

## Magic Constants
- \__LINE__	The current line number of the file.
- \__FILE__	The full path and filename of the file with symlinks resolved. If used inside an include, the name of the included file is returned.
- \__DIR__	The directory of the file. If used inside an include, the directory of the included file is returned. This is equivalent to dirname(__FILE__). This directory name does not have a trailing slash unless it is the root directory.
- \__FUNCTION__	The function name, or {closure} for anonymous functions.
- \__CLASS__	The class name. The class name includes the namespace it was declared in (e.g. Foo\Bar). Note that as of PHP 5.4 - \__CLASS__ works also in traits. When used in a trait method, __CLASS__ is the name of the class the trait is used in.
- \__TRAIT__	The trait name. The trait name includes the namespace it was declared in (e.g. Foo\Bar).
- \__METHOD__	The class method name.
- \__NAMESPACE__	The name of the current namespace.
- ClassName::class	The fully qualified class name. See also ::class.

## Architectural Patterns
- Coupling (tight coupling)
- Traditional SOA (looser coupling)
- Microservices (decoupled)

## Performance Optimization
- Single vs Double quotes
- PHP Version
- Count function in loops
- Closing connections (database, opening files)
- Static methods/properties use fewer resources (skips class instantiation)
- Minify assets (e.g. JS, CSS)
- Use CDN

## Packages
- Tyk (API Gateway with: OAuth, versioning, quotas, etc)
- Rabbit MQ (Message Broker)
- Redis (in-memory database, message broker-ish)
- Laravel (PHP Framework)
- Symphony (PHP Framework)
- Apache Kafka (Streaming Platform)
- GraphQL (Query Language for APIs)

## Official Documentation
- Language Reference https://www.php.net/manual/en/langref.php
- Functions https://www.php.net/manual/en/funcref.php
- Features https://www.php.net/manual/en/features.php
- Core https://www.php.net/manual/en/internals2.php
- Appendices https://www.php.net/manual/en/appendices.php
- Objects https://www.php.net/manual/en/oop5.intro.php
- Objects Changelog https://www.php.net/manual/en/language.oop5.changelog.php

## Useful books
- PHP 7 Data Structures and Algorithms
- The art of scalability
