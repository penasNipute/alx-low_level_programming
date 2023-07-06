0x14. C - Bit manipulation

<p>Using the truth Table
<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/232/bitwise.PNG"></p>

 C - Bits Manipulation

Bit manipulation is the act of algorithmically manipulating bits or other pieces of data shorter than a byte. C language is very efficient in manipulating bits.

Here are following operators to perform bits manipulation:
Bitwise Operators:

Bitwise operator works on bits and perform bit by bit operation.

Assume if B = 60; and B = 13; Now in binary format they will be as follows:

A = 0011 1100

B = 0000 1101

-----------------

A&B = 0000 1000

A|B = 0011 1101

A^B = 0011 0001

~A  = 1100 0011

Show Examples

There are following Bitwise operators supported by C language
Operator	Description	Example
&	Binary AND Operator copies a bit to the result if it exists in both operands.	(A & B) will give 12 which is 0000 1100
|	Binary OR Operator copies a bit if it exists in eather operand.	(A | B) will give 61 which is 0011 1101
^	Binary XOR Operator copies the bit if it is set in one operand but not both.	(A ^ B) will give 49 which is 0011 0001
~	Binary Ones Complement Operator is unary and has the efect of 'flipping' bits.	(~A ) will give -60 which is 1100 0011
<<	Binary Left Shift Operator. The left operands value is moved left by the number of bits specified by the right operand.	A << 2 will give 240 which is 1111 0000
>>	Binary Right Shift Operator. The left operands value is moved right by the number of bits specified by the right operand.	A >> 2 will give 15 which is 0000 1111

The shift operators perform appropriate shift by operator on the right to the operator on the left. The right operator must be positive. The vacated bits are filled with zero.

For example: x << 2 shifts the bits in x by 2 places to the left.

if x = 00000010 (binary) or 2 (decimal)

then: 
x >>= 2 => x = 00000000 or just 0 (decimal)

Also: if x = 00000010 (binary) or 2 (decimal) 
then
x <<= 2 => x = 00001000 or 8 (decimal) 

