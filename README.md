# BrainFuck-Compiler
BrainFuck Compiler Implementation in C

<b>
>  Increment Pointer
<  Decrement Pointer
-  Decrement Value in Current Pointer
+  Decrement Value in Current Pointer
.  Print Value in Current Pointer as Character
{  Print Value in Current Pointer as Integer (Very Useful while debugging)
,  Input Value as Charachter
}  Input Value as Integer
</b><hr>
<h4> Difference Between traditional BrainFuck Compiler and this one </h4>

BrainFuck Compiler uses fixed size of 1 byte array to store data. <br>
If you will use more than allocated memory than your program could crash. <br>
And usage of less memory than allocated is wastage of memory. <br>
Mine Compiler uses dynamically allocated array which increases size of array according to need <br>
 <br>
This compiler Provides input and output feature as Integer <br>
 <br>
C source code generated by this compiler is more readable <br>
<hr>
<h4> USAGE </h4>
./BrainFuck source.bf output.exe
