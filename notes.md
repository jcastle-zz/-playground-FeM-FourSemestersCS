# FeM Four Semesters of CS in Five Hours

- Taught by Brian Holt
- Course materials - http://btholt.github.io/four-semesters-of-cs/

## Introduction to CS

- CS is a science of tradeoffs - should I have more readable code, should it go faster - 90% of the time it's about communication for those who come after you
- Should favor code readability over performance
- Useful to help making tradeoffs in head - make things faster, make better code
- Intro to Algorithms by Cormen et al. - https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844

## Big O

- Used to examine algorithm efficiency - derived from mathematics
- Care about orders of magnitude types of difference in speed of an algorithm
- Can be used for time (algorithm processing) and spatial analysis (space/memory)
- Looking for loops, that's where most time will be spent
- Constant time O(1) means there are no loops in the code
- O(log n) denotes a recursive algorithm, as you add more elements to a list, it will take less time for each element - also true with merge, sort, trees

## Recursion

- CodePen Recursion Example - https://codepen.io/jcastle/pen/VwjPEEm?editors=0010

- Define something in terms of itself
- Recursion not useful in english, but useful in CS
- Define a function that calls itself
- Each level of recursive call maintains it's own state
- Useful for some problems but carries a cost - making more calls to the function adds more functions to the stack
- Generally ignore the cost but when you call a function 100 to 200 times then there is some impact
- Stack overflow - recurse so far that stack builds up
- First line is the base case, identifies when the recursion stops
- Can do things up and down the stack
- Real application - Fibonacci Sequences - the two previous terms/numbers added together
- Simple recursion can be accomplished with a loop

## Sorting Algorithms
