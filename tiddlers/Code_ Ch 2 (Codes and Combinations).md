!! 2.1 (Morse Code and the Telegraph)
-> The telegraph provides a good intro to computer hardware. This includes the challenges that came with decoding messages sent in Morse – sending the code is easier than decoding it.

Inventor of Morse code was Samuel Finley Breese Morse (1800’s)

---

!! 2.2 (Organizing Morse Code Characters)
-> Organize Morse code by grouping its characters based on how many dots and dashes they have.
* This gives us four tables containing: 2 plus 4 plus 8 plus 16 codes for a total of 30 letters (the 4 extra are accented letters)

Organizing them in this way makes translating Morse code easier.

But this organization method also reveals a pattern in the size of the four tables: **Each table has twice as many codes as the table before it.**
* Each table has all the codes in the previous table followed by a dot
* Each table also has all the codes I the previous table followed by a dash

Here’s a summary of this trend:

|!No. Of Dots & Dashes	|!No. Of Codes |
|!1 |!2 |
|!2 |!4 |
|!3 |!8 |
|!4 |!16 |
//(30 possible characters)//

a.k.a.

|!No. Of Dots & Dashes	|!No. Of Codes |
|!1 |!2 |
|!2 |!2*2 |
|!3 |!2*2*2 |
|!4 |!2*2*2*2 |
//(30 possible characters)//

> Once we have **a number multiplied by itself,** we can use exponents to show powers.
* So 2*2*2*2 can be written as 2^4 (two to the fourth power)
* So 2, 4, 8, and 16 are all powers of 2 because you can calculate them by multiplying 2 by itself. So:

|!No. Dots & Dashes |!No.  Codes |!No. Characters |
|!1 |!2^1 |!2 |
|!2 |!2^2 |!4 |
|!3 |!2^3 |!8 |
|!4 |!2^4 |!16 |
|!//(30 possible characters if you add the last column so far)// |
|!5 |!2^5 |!32 |
|!6 |!2^6 |!64 |
|!7 |!2^7 |!128 |
|!8 |!2^8 |!256 |
|!9 |!2^9 |!512 |
|!10 |!2^10|!1024 |

We can summarize this table data in this formula:
> number of codes = 2^number of dots and dashes
* powers of 2 tend to show up a lot in codes

!!! A Treelike Table
-> An even easier way to decode Morse

[img[Code Image 2: Using Trees to Decode Morse Code]]

Constructing a table like this was probably necessary for defining Morse code in the first place.
* it ensures you don’t accidentally use the same code for two different letters
* you’re also assured of using all the possible codes without making the sequences of dots and dashes unnecessarily long

This table could also be continued for codes of five dots and dashes plus more (e.g. 2^5= 62 possible characters, 2^6= 126 possible characters)

By the time you get to 2^6/126 characters in Morse code, a lot of the longer codes are left *undefined*.

> **Undefined:** In this context, it refers to a code that doesn’t stand for anything.

---

!! 2.3 (Binary Entities)
Morse code = a binary code because the components of the code consist of only two things – a dot and a dash
* similar to a coin which can only land on its head or this side

> **Binary:** literally meaning ‘two by two’

A binary object = a coin
A binary code = Morse

Binary entities are always described by powers of two.

!!!! Combinatorics / Combinatorial Analysis
-> Analyzing binary codes is a simple exercise in this branch of mathematics

Combinatorial analysis is used most often in probability and statistics
* it involves determining the number of ways things (like coins and dice) can be combined.
* also helps us understand how codes can be put together and taken apart