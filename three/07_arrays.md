!SLIDE
# Arrays

!SLIDE smbullets incremental
# Arrays: the basics

* One of JavaScript's few built-in data types
* An ordered, zero-indexed list with O(1) access to arbitrary elements
* Elements are accessed with square bracket notation and numeric indices

!SLIDE smbullets incremental
# Array lengths

* JavaScript arrays are dynamically sized
* You don't have to decide up-front how long they are
* The `length` property reflects the number of elements in the array
* If you `delete` an element of the array, the length won't change
* But if you use `pop` or `unshift`, it will

!SLIDE smbullets incremental
# Array methods

* Several types of methods
* Mutator methods change the array
* Accessor methods just return information
* Iteration methods call a function on every element

!SLIDE smbullets incremental
# Array accessor methods

* `concat` joins two arrays
* `join` joins the elements into a string
* `slice` extracts part of the array
* `indexOf` returns the _first_ index of that element (or `-1`)
* `lastIndexOf` returns the _last_ index of that element (or `-1`)

!SLIDE smbullets incremental
# Array mutator methods

* `reverse` does what you'd expect
* `pop` removes the last element and returns it
* `push` adds elements to the end of the array
* `shift` removes the first elements and returns it
* `unshift` adds elements to the beginning of the array
* `splice` removes some elements and replaces them with others

!SLIDE smbullets incremental
# Array iteration methods 1

* `forEach` calls a function for each element in the array
* `every` returns whether all elements pass some test
* (Think of `every` as the `&&` operation on an array)
* `some` returns whether at least one element passes some test
* (Think of `some` as the `||` operation on an array)

!SLIDE smbullets incremental
# Array iteration methods 2

* `filter` returns a new array containing only elements that pass some test
* `map` returns a new array consisting of the results of applying a function to each element
* `reduce` and `reduceRight` squash the array to a single value
