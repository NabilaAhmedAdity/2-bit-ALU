#2-bit ALU

This 2-bit ALU performs the following task:
- Not
- And
- Or
- Xor
- Addition
- Subtraction
- Multiplication

First I created 1-bit ALU. Then consider this 1-bit ALU as an object and used to build 2-bit ALU.

# How to operate?

For **not**, put 0 in both the multiplexers. It only alters the bits of A. See an example in image 'not.png'.

For **and**, put 001 in first multiplxer and 0 in second. See an example in image 'and.png'.

For **or**, put 010 in first multiplxer and 0 in second. See an example in image 'or.png'.

For **xor**, put 011 in first multiplxer and 0 in second. See an example in image 'xor.png'.

For **addition**, put 100 in first multiplxer and 0 in second. Make sure that sub is 0. See an example in image 'add.png'.

For **subtraction**, put 100 in first multiplxer and 0 in second. Make sure that sub is now 1. See an example in image 'sub.png'.

For **multiplication**, the value in first multiplexer doesn't matter but the value in second multiplexer must be 1. See an example in image 'mul.png'. 
