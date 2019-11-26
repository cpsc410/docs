# Visualization Project

## Purpose
We designed a metro map to display the code files and the contributors for a given GitHub project.

![alt text](FinalRender.png)

The nodes represent the file names and the different coloured lines represent different author who has contributed to the project being analyzed.

## Usage
To run the project navigate to [here](https://github.com/cpsc410/runner/blob/master/README.md) and follow the instructions

## Use Cases
We think that this project can be very useful for:
- see who worked on a specific file
-- this could be especially helpful when trying to contact someone to fix a bug
- see what the division of labour was
- see who contributed most to files
- see top contributor(s)


## Performed Analyses
We utilized three different analyses for this project; Lexical, Syntactical and Semantic.

### Lexical Analysis
- done on static input files
- used for tokenizing the stats obtained by running the shell script (getStatsAll.sh)

### Syntactical Analysis
- done on static input files
- used for creating grammar for the stats.txt input file
- the grammar was included in the ast folder which contained the AuthorNode and FileNode

### Semantic Analysis
- used for identification of the meaning
- used dynamic analysis when adding symbol and values in the symbol table -- it could only be populated when the program was running 

## Prototype Progression
See PrototypeProgression.pdf

## User Studies
See UserStudies.pdf

