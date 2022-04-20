# CMPS 2200 Recitation 7
## Answers

**Name:**____Will Rodman________


Place all written answers from `recitation-07.md` here for easier grading.


- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt        |      1340        |    1141       |   1    : 1.17  
alice29.txt   |      1039367     |    1050386    |   1.01 : 1
asyoulik.txt  |      876253      |    827516     |   1    : 1.06
grammar.lsp   |      26047       |    26097      |   1    : 1
fields.c      |      78050       |    73120      |   1    : 1.06

Huffmen encoding has a higher compression rate when there is a low 
quantity of different characters.

- **e.**

In this case, the size of the Huffmen encoding would scale in proportion to files
quantity of different characters. Since the quantity of different characters 
varies across different files, this scaling factor would not be constant across 
different files. 

