## Lexical Analyzer

### Overview
The Lexical Analyzer is a program designed to scan C source code and identify the different tokens present within the code. These tokens can include keywords, identifiers, constants, string literals, or symbols.

### Functionality
The input to the Lexical Analyzer is a C source code file. Upon processing this input, the program generates a sequence of tokens along with their respective types.

### Tech Stack
The Lexical Analyzer is implemented in the C programming language.

### Challenges
The main challenges encountered during the implementation of the Lexical Analyzer were:
- Identifying the various types of tokens in the C language.
- Handling special cases such as comments and string literals.
- Developing efficient algorithms for scanning the source code.

### Lexical Analysis in C
Lexical analysis is the initial phase of a compiler, responsible for breaking down the source code into a sequence of tokens, each representing the smallest unit of meaning in the programming language.

In C, lexical analysis can be implemented using methods such as finite state machines (FSM). An FSM model helps in recognizing patterns within the input symbols.

The Lexical Analyzer follows these steps:
1. Starts in the initial state.
2. Reads the next input symbol and transitions to the next state based on the current state and input symbol.
3. Continues reading input symbols and transitioning to new states until reaching a final state.
4. Upon reaching a final state, recognizes a token and outputs it, then resets to the initial state.

### Conclusion
Lexical analysis is crucial in compiler design as it forms the foundation for further processing of the source code. The Lexical Analyzer serves as a fundamental component in this process, facilitating the transformation of C source code into a structured sequence of tokens.
