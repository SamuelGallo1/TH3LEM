TH3LEM
=======

## developed by: Samuel Cano-Gallo
## version: 0.0

# History
TH3LEM (_IPA:θɹˈiːləm_) is a theoretical computer architecture based on 3-level-logic created by an Computer science Tech Student.  
The name stands for **Theoretical 3-level machine** or **Theoretical 3-level machine architeture** as Th3lema (a pun for the religion) 
...inspired by MARIE and Malbolge and more...to finish.

# Introduction  to th3mel arithmetic and 3 value logic

Arithmetic
===============
Every arithmetic operation could be defined as an abstraction of addition, for example a subtraction could be defined as a+b, where either a or b could be a negative number.
The common algorithm for summation of decimal numbers works as well to ternary systems. Let's consider two numbers 54 and 26, then we have that 4+6=10, 10+50+20 = 80, the number 10 is represented commonly with a carry. 
In ternary we got that
54 = 2000 and 26 = 222
we have then that 
2000+222=2222 where the actual value is equal that in decimal system.

## transformation decimal-ternary

sum of digits in a Three-value system, has similarity to binary where defined as N(b,d)=b^d -1 where b(base) & d(digits), as an example let's transfor the number 60 to ternary and the number 1012 to decimal:


1012 -> (1x3^3)+(0x3^2)+(1x3^1)+(2x3^0)= 27+0+3+2 =32

60 -> (the trasnformation is given in table bellow) 
|division by 3| quotient | remainder | trit|
|---------|----------|------------|------|
|60/3	| 20  | 0 | 0|
|20/3	| 6  | 2 | 1|
|6/3	| 2   | 0 | 3|
| 2/3	| 0   | 2 | 4|
 
The result *in trits of the number 60 is 2020.*

Although there are more ways to do convert both numbers, the ways above are easier to inplement into simplier algorithms

## Tryte

In equivalence to the byte a tryte is the collections of multiple trits, in Th3lem a tryte is composed by 6 trits and it's representation is by two septemvigesimal numbers, similar as in binary that each byte is represented by pairs of 4 bits

#### septemvigesinary

|0|1|2|3|4|5|6|7|8|
|-|-|-|-|-|-|-|-|-|
|9|A|B|C|D|E|F|G|H|
|I|J|K|L|M|N|O|P|Q|

###### comparison with decimal
|0|1|2|3|4|5|6|7|8|9|
|-|-|-|-|-|-|-|-|-|-|
|10|11|12|13|14|15|16|17|18|19|
|20|21|22|23|24|24|25|26| | | |
