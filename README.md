# Hackerank-System.in-System.out

## Happy Coding :)

### For those who are new to programming and to Java, I thought this is interest and important concept of primitive data type nextInt(), nextDouble() vs. reference type next(), nextLine()

### Challenge:
Input Format
There are three lines of input:

The first line contains an integer.
The second line contains a double.
The third line contains a String.
Output Format

There are three lines of output:

On the first line, print String: followed by the unaltered String read from stdin.
On the second line, print Double: followed by the unaltered double read from stdin.
On the third line, print Int: followed by the unaltered integer read from stdin.

### Note: 

**If you use the nextLine() method immediately following the nextInt() method, recall that nextInt() reads integer tokens; because of this, the last newline character for that line of integer input is still queued in the input buffer and the next nextLine() will be reading the remainder of the integer line (which is empty).**

### Sample input:
- 42
- 3.1415
- Welcome to HackerRank's Java tutorials!

### Sample output:
- String: Welcome to HackerRank's Java tutorials!
- Double: 3.1415
- Int: 42
