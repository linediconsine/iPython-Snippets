# Work in progress - 

An idea about *python Data science* best practices

### Style
Follow [PEP 8][], when sensible.

#### Naming

- Variables, functions, methods, packages, modules
    - `lower_case_with_underscores`
- Classes and Exceptions
    - `CapWords`
- Protected methods and internal functions
    - `_single_leading_underscore(self, ...)`
- Private methods
    - `__double_leading_underscore(self, ...)`
- Constants
    - `ALL_CAPS_WITH_UNDERSCORES`
   
#### Avoid one-letter variables (esp. l, O, I).

### Code good practices
#### Try to avoid *for* and use *apply* or *map* function [ vectorization ]
#### [On jupyter notebooks] if I execute two times the same code block this should not change compare to 1 execution
#### Use Checkpoints where you save data and explain what you archive
#### Comment! Explain your code, the yoursel of the future will be very happy about that

References:
https://gist.github.com/sloria/7001839
