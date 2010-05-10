!SLIDE
# 1: Values & Types

!SLIDE smbullets
# Examples of values

* `5`
* `"Foo"`
* `null`
* `undefined`
* `true`
* `Infinity`
* `NaN`

!SLIDE smbullets incremental
# Types

* Undefined
* Boolean
* Number
* String
* Object
* Function

!SLIDE code

    typeof this.doesnt_exist; // -> "undefined"
    typeof false;             // -> "boolean"
    typeof true;              // -> "boolean"
    typeof 1;                 // -> "number"
    typeof 1.01;              // -> "number"
    typeof 1e6;               // -> "number"
    typeof "foo";             // -> "string"
    typeof {};                // -> "object"
    typeof function() {};     // -> "function"

!SLIDE code

    typeof Infinity;          // -> "number"
    typeof NaN;               // -> "number"
    typeof null;              // -> "object"
    typeof [];                // -> "object"
    typeof /^.*$/;            // -> "function"
    typeof typeof foo;        // -> "string"

!SLIDE bullets
# Undefined

* Only one value, `undefined`
* Declared but uninitialised variables have this value

!SLIDE bullets
# Booleans

* Only two values
* `true` and `false`

!SLIDE bullets
# Numbers

* Integers: `0`, `5`
* Floating-point numbers: `3.14`, `3.7e-5`
* `Infinity`
* `NaN`

!SLIDE bullets
# Strings

* `"Foo"`
* `'Bar'`
* `"\n"`

!SLIDE bullets incremental
# Objects

* Object literals
* Objects: `{foo: 1, bar: 2}`
* Arrays: `[1, 4, 9]`
* Regular expressions: `/^(foo|bar)$/`
* `null`

!SLIDE bullets
# Functions

* Functions are _callable_
* `(function() {})()` creates a function and then calls it
* Functions are also objects
