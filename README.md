# COOL Compiler
The goal of the assignment was to write a lexical analyser for the Classroom Object Oriented Language (COOL) using Antlr, an automatic parser generator written in Java.

The code for the grammar is present in '\src\Lexer_grammar.g4'

The grammar is written to extract the following structures in COOL: 
1. Integer and Bool constants 
2. Other keywords and Identifiers 
3. Comments
4. Whitespaces
5. Strings

A) Lexer Function <br />
it is used to verify the structure of Keywords such as "IF, WHILE, IN"

B) Parser Function <br />
it is used to verify the structure of the lines consisted of keywords and that it's a verified code lines

## Usage
The Test cases used in this project placed in '\src\bad.cl' and '\src\good.cl' <br />
Open Project using Java IDE and input the test file in main:
```java
String file = "src/bad.cl";
```
The output file will be in the src folder with the name of '(same test filename)+-lex' for example in this case 'bad.cl-lex'

## Team Member
Ebrahim Magdy <br />
Fady Samir <br />
Rehab Naguib <br />
Bishoy Samy
