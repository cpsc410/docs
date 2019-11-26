# Visualization Project

## Purpose
A metro map  was designed to display the code files and the contributors for a given GitHub project.

Nodes represent the file names ,and the different coloured lines represent different authors who contributed to the project being analyzed.

## Use Cases
This project can be beneficial for:
- see who worked on a specific file
-- this could be especially helpful when trying to contact someone to fix a bug
- determining the division of labour
- observing who contributed most to files
- displaying top contributor(s)


## Performed Analyses
Three different analyses were analyzed for this project; Lexical, Syntactical and Semantic.

### Lexical Analysis
- done on static input files
- used for tokenizing the stats obtained by running the shell script (getStatsAll.sh)

### Syntactical Analysis
- done on static input files
- used for creating grammar for the stats.txt input file
- the grammar was included in the ast folder which contains the AuthorNode and FileNode

### Semantic Analysis
- used for identification of the meaning
- used dynamic analysis when adding symbol and values in the symbol table -- it could only be populated when the program was running 

## Prototype Progression
See PrototypeProgression.pdf

## User Studies
See UserStudies.pdf


