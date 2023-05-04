Download Link: https://assignmentchef.com/product/solved-csc-230-lab-1-lab-environment-and-number-systems
<br>
<h1>II. Number Systems</h1>

In the computer system, we need to know how many bits (storage space) are used. For example, let’s count the number of students in the lab. In decimal number system, we just need two digits. In the binary number system, how many bits do we need?

Let’s do counting up in decimal, binary and hexadecimal. The conversion table up to the decimal value of 22 is provided below. Having a systematic way of counting, you should be able to come up with a conversion table that is indefinitely long on your own

<h1>IV. Exercises</h1>

<ol>

 <li>Why do we use 5 bits in the table in part II (the number of students attending the lab)? Can we use only 4-bits instead?</li>

 <li>How many different values can be represented by 6 bits?</li>

 <li>There are 194 students registered in CSc 230, what is the minimum number of bits needed to represent this number in binary (assume it is an unsigned number)?</li>

 <li>Convert the following positive integer numbers:

  <ol>

   <li>0b1001101 to decimal</li>

   <li>261 to binary</li>

   <li>153 to hexadecimal</li>

   <li>0x1FE to decimal</li>

  </ol></li>

</ol>

<ol start="5">

 <li>Convert the following numbers using 2’s complement notation:

  <ol>

   <li>-63 to binary</li>

   <li>-123 to hexadecimal</li>

   <li>0b101011 to decimal</li>

   <li>0b001110 to decimal</li>

  </ol></li>

</ol>




<ol start="6">

 <li>What are the minimum and maximum values (in decimal) represented by a 4-bit binary number:</li>

 <li>a) as an unsigned number? b) as a signed number (2’s complement)? How about 8 bits, 16 bits? Can you come up with an equation for any number of bits, let’s say k?</li>

</ol>

For example, given a 2-bit number, the answer is:

Number of bits                                  Unsigned                        Signed

2                                                             [0, 3]                                   [-2,1]

<ol start="7">

 <li>What is the result of bitwise AND operation on 0b10110010 with 0b11110000?</li>

 <li>What is the result of bitwise XOR operation on 0b11000101 with 0b11110000?</li>

 <li>What is the result of the logical left-shift operation on 0b01011101? How about right-shift?</li>

 <li>Recall that the position of each bit in a binary number is associated with its power; for example, in one byte, the positions are 2<sup>7</sup>2<sup>6</sup>2<sup>5</sup>2<sup>4</sup>2<sup>3</sup>2<sup>2</sup>2<sup>1</sup>2<sup>0</sup>. What is the 8-bit binary number x (also called a mask) to be used if we want to clear the bits at positions 2, 3, 5, and 7 in a given byte?</li>

</ol>