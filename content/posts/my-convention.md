---
title: "Making my own convention for coding"
date: 2023-09-25T01:30:00+05:30
draft: false
---

# Making my own convention to write code
## Preface
I have seen multiple 'conventions' for how to write code. Every organization, institution or just a language documentation would sometimes have some sort of convention to write code. I always saw each convention and felt like it just wasn't it for me, either too complex or constricting.
So, I decided to create my own basic convention with simple rules that fit my usage.
### Functions
Functions should always be in lowercase, and use underscore instead of spaces. Naming should be simple and straight to the point. Use prefixes for common words, for example 'max' for maximum or 'key' for well, key. Don't make large function names, keep it short and simple.
### Comment out your system of units
It is a very common problem indeed. Converting KG's to LB's, or metres to feet and more of those problems. To avoid confusion, specify any variable (or sometimes function) with their unit.
### Variables

Variables are special, they can have multiple functions. 
- Integers, floats, double etc. (that represent numbers) should be represented via lowercase + underscore. 
Eg. max_numbers, age.
- Strings, characters, booleans should be represented with Normal case. 
Eg. Name, Letter.
- Booleans, if use 'is' in front of them, should be snake case. 
Eg. isReal, isOff.
- Vectors, should use a specification letter that usually specifies its job (should also be commented), an underscore and then Normal case.
Eg. V_Velocity, V_Acceleration //V applies for movement
### Constants
Constants have to be strictly all uppercase with underscores.
Eg. PI, RATIONAL_NUMBER
### Enums and Structs
Enums and structs have to be Normal case, and no spaces or underscores.
Eg. enum PersonData.
All data inside enum should be capitals with underscore.
### General
Don't exceed more than 4 tabs of line. Make sure the line isn't too long.
Also, ensure that the code file does not exceed 1,000 lines. Best practice is to keep at maximum of 650 lines. Also make sure you properly format the code.
## Conclusion
In my honest opinion, I believe that every language cannot be the same, so adjustments can be made. This is only a convention for my code, I hope you see how clean this can make the code look.

