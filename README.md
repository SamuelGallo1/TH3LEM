TH3LEM
=======

## developed by: Samuel Cano-Gallo
## version: 0.0

# History
TH3LEM (_IPA:θɹˈiːləm_) is a theoretical computer architecture based on 3-level-logic created by an Computer science Tech Student.  
The name stands for **Theoretical 3-level machine** or **Theoretical 3-level machine architeture** as Th3lema (a pun for the religion) 
...inspired by MARIE and Malbolge and more...to finish.

# Introduction  
As said in the **History** part Th3lem is based on a three-value-logic with the simplicity of MARIE...math...logic and more...to finish.
# Instructions  
Each instruction is 12 trits of lenght being the first 3 trits the Opcode (operation code) and the rest representing the address
|TYPE|Instruction|Opcode|Explanation|
|----|-----------|------|----------|
| Arithmetic| ADD X| 100| .....|
| | SUB X | 101 | ....|
| | MUL X | 102 | ....|
|Data Transfer| LD X| 120 |..... |
| | STR X | 121 |....|
|Jump instructions| JMS X| 001 |Store contents of the counter in X, then jump to the next address|
| | JMP X| 002 |Jump to X uncondisionally|
| | JMC C, X| 010 | Jump to X intruction if C (condition) is equal: 
* 0: AC = value; AC=0
* * 1: AC > value; AC>0
  * * 2: AC < value; AC<0| 
