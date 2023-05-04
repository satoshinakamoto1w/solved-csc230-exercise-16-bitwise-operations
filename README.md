Download Link: https://assignmentchef.com/product/solved-csc230-exercise-16-bitwise-operations
<br>
<strong>Bitwise Operations</strong>

On the course homepage, you’ll find a source file, bitwise.c, and an expected output file.  You can also download these using the following curl commands:

curl -O https://www.csc2.ncsu.edu/courses/csc230/exercise/exercise16/bitwise.c curl -O https://www.csc2.ncsu.edu/courses/csc230/exercise/exercise16/expected.txt

This program contains three empty functions.  You get to fill in the functions to accomplish a few simple bit manipulation tasks.

<ul>

 <li>The job of the clear6() function is to clear the six high-order bits in the unsigned short value passed to it. The function returns the resulting value.  All other bits should be unchanged.</li>

 <li>The set9() function takes an unsigned short value, passed by address. Its job is to set the 9 low-order bits in the given value (i.e., set them to 1).  All other bits should be unchanged.</li>

 <li>The set7() function also takes an unsigned short value passed in by address along with a boolean flag. If the flag is true, this function should set bit 7 in the given short value.  If the flag is false, it should clear the bit.  All other bits should be unchanged.</li>

</ul>

Once your program is complete, you should be able to run it as follows:

$ ./bitwise

—– clear6 —–

03ff

0000

037d

029e

—– set9 —–

ffff 01ff b9ff 19ff

—– set7 —–

ff7f 0080

5af0

4f96

When you’re done, submit the source, bitwise.c, to the exercise_16 assignment on Moodle.