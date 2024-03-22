# Lexical Analysis
### What is Lexical Analysis?
Lexical analysis, also known as scanning or tokenization, is the first phase of the compilation process in programming language processing. It involves analyzing a sequence of characters in a source code file and converting them into a sequence of tokens. Tokens are the smallest meaningful units in a programming language, such as keywords, identifiers, operators, and literals.

### Purpose of Lexical Analysis
The primary purpose of lexical analysis is to break down the source code into tokens that can be easily processed by the compiler or interpreter. By identifying and categorizing tokens, lexical analysis lays the foundation for subsequent phases of compilation, such as parsing and semantic analysis.

### Components of Lexical Analysis
The main components of lexical analysis include:
**Input Buffer:** A buffer that holds the source code text to be analyzed.
**Lexer (Scanner):** The component responsible for scanning the input buffer, identifying tokens, and generating lexemes.
**Token:** A categorized unit of the source code, representing a keyword, identifier, operator, etc.
**Lexeme:** The actual sequence of characters in the source code that corresponds to a token.

### Lexical Analysis in the Compilation Process
Lexical analysis is the first step in the compilation process. It takes the raw source code text as input and produces a stream of tokens as output. These tokens are then passed to the next phase of compilation, typically the parser, which constructs a parse tree or syntax tree based on the tokens.

### Tokenization Process
The tokenization process involves several steps:
**Scanning:** The input buffer is scanned character by character, and tokens are identified based on predefined patterns.
**Token Recognition:** The lexer recognizes patterns corresponding to predefined tokens, such as keywords, identifiers, and symbols.
**Lexical Error Handling:** Lexical errors, such as invalid characters or unrecognized tokens, are detected and reported.

## About This Project
This project is a simple Java program that demonstrates lexical analysis of a source code file. It reads the source code file, tokenizes it, and outputs the tokens along with their lexemes and line numbers. The program serves as a basic illustration of the lexical analysis process in programming language processing.
This project is a simple Java program for performing lexical analysis of a source code file. Lexical analysis is the process of converting a sequence of characters into a sequence of tokens, which are meaningful units in a programming language. The program reads a source code file, tokenizes it, and outputs the tokens along with their lexemes and line numbers.

## Getting Started
To use this program, follow these steps:
1. **Clone the Repository:** Clone this repository to your local machine.
2. **Navigate to the Project Directory:** Change your current directory to the project directory.
3. **Compile the Java Program:** Compile the LexicalAnalyzer.java file using the Java compiler.
4. **Run the Program:** Execute the compiled program, providing the path of your source code file as an argument.

