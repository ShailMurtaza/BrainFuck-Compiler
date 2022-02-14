# BrainFuck-Compiler
BrainFuck Compiler Implementation in C

<i>
> Increment Pointer
< Decrement Pointer
- Decrement Value in Current Pointer
+ Decrement Value in Current Pointer
. Print Value in Current Pointer as Character
{ Print Value in Current Pointer as Integer (Very Useful while debugging)
, Input Value as Charachter
} Input Value as Integer
</i>
<h3> Difference Between traditional BrainFuck Compiler and this one </h3>

BrainFuck Compiler uses fixed size of 1 byte array to store data.
If you will use more than allocated memory than your program could crash.
And usage of less memory than allocated is wastage of memory.
Mine Compiler uses dynamically allocated array which increases size of array according to need

This compiler Provides input and output feature as Integer

C source code generated by this compiler is more readable
