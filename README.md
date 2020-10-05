#Lexical Analyzer
Lexical Analyzer is the first phase of a compiler. Lexical Analysis is the process of taking an input string of characters such as the source code of a computer program and producing a sequence of symbols called lexical tokens, which may be handled more easily by a parser. A program or function which performs lexical analysis is called a lexical analyzer, lexer, or scanner. A lexer often exists as a single function which is called by a parser or another function. Here a lexical analyzer is designed to recognize identifiers, operators, keywords as well as integers that are written as a part of the source program.
 A token is a string of characters, categorized according to certain rules into different symbol types. (e.g. Identifier, Operator). Tokens are frequently defined by regular expressions, which are understood by a lexical analyzer generator such as lex. The lexical analyzer (either generated automatically by a tool like lex, or hand-crafted) reads in a stream of characters, identifies the lexemes in the stream, and categorizes them into tokens. The process of forming tokens from an input stream of characters is called tokenization. 
In this project the lexical analyzer uses C language, reads the input values and further performs the following tasks:
1.	Reads the input characters from the source program.
2.	Identifies the tokens according to the types defined using functions after dividing the source code.
3.	Eliminates white spaces in the form of blanks, tab and newline characters.
4.	Correlates error messages/invalid identifiers if any.
