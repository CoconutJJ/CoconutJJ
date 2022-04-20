### Hi there 👋

You can learn more about me at [davidyue.live](https://davidyue.live/)

### How to write neat code

I think I've found an almost universal guide to writing neat/readable code. The
idea is to make your code look like a linear list instead of a nested
tree/pyramid.

1. Look through your code and find the deepest local scope (in many languages
   this is the largest indentation level). Reduce this code's scope depth by
   refactoring it into a function.

2. Keep the amount of code inside a single non-function block to a minimum. Try
   to write as much code that runs without condition as possible relative to the
   surrounding block. Avoid branching at all costs!
