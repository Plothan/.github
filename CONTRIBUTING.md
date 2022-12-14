# Contribution to Plethan's Software
We always welcome contributions to our software *(unless explictly said otherwise)*, however, we have a few guidelines in place for enforcing general-purpose guidelines that all of our software follows.

### Optimization
We always strive to optimze our software speed, however, we should have clear guideliens that state what kind of optimization we look for at Plethan for our software.
These are a few types of optimization that we tend to accept:
1. **Stable Optimization:** We look for optimization that always cause positive effect on the Software's speed regardless of the number of inputs. O(1) is often assoicated with this optimization
2. **Use the right algorithms/data structures:** Always use the right algorithm and data structure for your use case. An array is good, but a dictionary is awesome for its high read spead.

These are a few types of optimization we tend to reject:
1. **Premature optimization:** We always reject optimization that affect the speed of the Software, with a huge cost on the readability of the Software source code.
2. **Magic:** We reject kind of optimization that use niche features that affact the predicitability of the Software's output.

### Readability
We always try to maintain the readability of our Software, as such, we follow the [Roblox Lua Style guide](https://roblox.github.io/lua-style-guide/); so write your code accordingly to that style guide. However there are a few guidelines that we want to explictly mention, regardless of their existence in the style guide:
1. **Naming:** You should name your variables depending on their behavior. For example, boolean operations are often represented as a yes or no questions, therfore, you should name the variables *isX* rather than *isNotX*. And an event handler should be named *OnSomething* rather than *Something*, and a function should be named *DoSomething* rather than *SomethingEnabler*.

