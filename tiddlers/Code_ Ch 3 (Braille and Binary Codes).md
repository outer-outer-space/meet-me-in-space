## 3.1 (An Introduction to Methods Historically Used to Help the Blind Read)
Samuel Morse wasn’t the first to:
* translate the letters of written language into an interpretable code
* be remembered more as the name of his code than as himself

Louis Braille was born in France in the early 1800’s. 

### Early Attempts to Help the Blind Read
Valentin Haüy (who was not blind) invented a system of raised letters on paper that could be read by touch, but it was difficult to use and was used infrequently.
* he was stuck in a paradigm where an ‘A’ was an ‘A’ was an ‘A’
* In the Flashlight Problem example, he would have tried drawing the ‘A’ with a flashlight – ineffectively

Charles Barbier devised écriture nocturne (a.k.a. night writing)
* this system used a pattern of raised dot and dashes on heavy paper
* intended for sue by soldiers in passing notes to each other in the dark when noise couldn’t be made
* but rather than using patterns of dot and dashes corresponding to letters of the alphabet, his system used patterns that corresponded to sounds, often requiring many codes for a single word

Louis Braille improved the system within three years (from the age of 12 to 15)

---

## 3.2 (Dissecting Braille Code)
In Braille, every symbol used in normal written language is encoded as one or more raised dots within a two by three cell. 
* The dots of the cell are commonly numbered 1 though 6


1	°	°	4

2	°	°	5

3	°	°	6

Example of braille character in non-raised notation:

1	•	°	4

2	°	•	5

3	•	°	6

Dots 1, 3 and 5 are raised. Dots 2, 4, and 6 are not raised.

> **The dots are binary!** Because a particular dot can be either flat or raised
* so we can combine what we know about Morse code and combinatorial analysis to Braille.
	* We know we have 6 dots which can be either flat or raised 
	* So we know the total number of combinations of 6 flat and raised dots is:
		* 2*2*2*2*2*2
		* 2^6
		* 64
	* So the Braille system is capable of representing 64 unique codes:

[img[Code Image 3: Braille]]

The first step in dissecting the code is looking at the basic lowercase alphabet.

[img[Code Image 4: Decoding Braille]]

^ These three rows show a pattern
1. Letters ‘a’ through ‘j’ use only the top four spots in the cell – dots 1, 2, 4, and 5
2. Letters ‘k’ through ’t’ exhibit the same pattern as row 1, except dot 3 is also raised
3. Letters ‘u’ through ‘z’ follow the same pattern as row 1, but ‘3’ and ‘6’ are also raised

#### Grade 2 Braille
-> A variation meant to speed reading and reduce space

In this variant, if letter codes appear by themselves, they stand for common words:
[img[Code Image 5: Grade 2 Braille]]

All of this still only described 31 out of a possible 64 codes.

A variant where dot 6 is raised for the lowercase row ‘a’ through ‘j’ is used for contractions, e.g. 
‘ch’ =
•	°
°	º
º	•

A variant where dot 6 is raised for the lowercase row ‘a’ through ‘j’, but which excludes the use of dots ‘1’ and ‘4’ is used for additional contractions and punctuation marks, e.g. 
‘was’ and a closing quotation mark =
°	°
°	•
•	•

These variants give us 51 codes so far.

The remaining variants help denote numbers, accents, capital letters, decimal points or emphasis depending on context.

---

## 3.3 (Summary)
Six binary elements (the dots) yield 64 possible codes, many of which perform ‘double duty’ depending on context.

### Precedence / Shift Codes
Two especially interesting elements are the number indicator and the letter indicator which undoes the number indicator.
* they alter the meaning of the codes that follow them
	* from letters to numbers
	* from numbers back to letters

> **Precedence / Shift Code:** Alters the meaning of all subsequent codes until the shift is done.

### Escape Codes
-> The capital indicator means only the following letter should be changed

> **Escape Code:** Lets you ‘escape’ from the routine interpretation of a sequence of codes and move to a new interpretation.

Both shift codes and escape codes are common when written languages are represented as binary codes.