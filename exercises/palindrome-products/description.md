Detect palindrome products in a given range.

A palindromic number is a number that remains the same when its digits are
reversed. For example, `121` is a palindromic number but `112` is not.

Given the definition of a palindromic number, we define a palindrome _product_
to be the product `c`, such that `a * b = c`, where `c` is a palindromic number and
 `a` and `b` are integers (possibly, but _not_ necessarily palindromic numbers).

For example, the palindromic number 9009 can be written as the palindrome
product: `91 * 99 = 9009`.

It's possible (and indeed common) for a palindrome product to be the product
of multiple combinations of numbers. For example, the palindrome product `9` has
the factors `(1, 9)` and `(3, 3)`.

Write a program that given a range of integers, returns the smallest and largest
palindromic product of factors within that range, along with all the factors in the range for that product.

## Example 1

Given the range `[1, 9]` (both inclusive)...

The smallest product is `1`. Its factors are `(1, 1)`.
The largest product is `9`. Its factors are `(1, 9)`, and `(3, 3)`.

## Example 2

Given the range `[10, 99]` (both inclusive)...

The smallest palindrome product is `121`. Its factors are `(11, 11)`.
The largest palindrome product is `9009`. Its factors are `(91, 99)` and `(99, 91)`.
