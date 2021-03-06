# Go: Series

Write a program that will take a string of digits and give you all the contiguous substrings of length `n` in that string.

For example, the string "49142" has the following 3-digit series:

- 491
- 914
- 142

And the following 4-digit series:

- 4914
- 9142

And if you ask for a 6-digit series from a 5-digit string, you deserve
whatever you get.

Note that these series are only required to occupy *adjacent positions*
in the input; the digits need not be *numerically consecutive*.

The tests are written using the `testing` package in the standard library.

To run a test file use the `go test` command:

    go test

## Source

A subset of the Problem 8 at Project Euler [http://projecteuler.net/problem=8](http://projecteuler.net/problem=8)

This exercise is from the [Go][go] track on [Exercism][exercism]

[exercism]: http://exercism.io
[go]: http://exercism.io/languages/go



