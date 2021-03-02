# Testing with Jest & Enzyme
## Challenge 1 - assertEquals()

The aim of the exercise is to demonstrate your problem solving and understanding of JavaScript by implementing something found in every unit testing tool - an "assertEquals" method.

* Fill in the "assertEquals" function such that it will correctly compare the passed "expected" vs "actual" parameters.
* You may add more functions.
* Credit will be given for approach, correctly identifying "failed" assertEquals, clean, testable code and coding style.

### Assert Equal Requirements list

| Expected   |      Actual      |  Result |
|----------|:-------------:|------:|
| "abc" |  "abc" | Function does not throw error |
| "abcef" |  "abc" | Throws error with message 'Expected "abcef" but found "abc"' |
| ['a'] |  {0: 'a'} | Throws error with message 'Expected type Array but found type Object'' |
| ['a', 'b', 'c'] |  ['a', 'b', 'c'] | Function does not throw error |
| ['a', 'b'] |  ['a', 'b', 'c'] | Throws error with message 'Expected array length 2 but found 3' |
