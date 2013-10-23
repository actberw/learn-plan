1. There are two ways to translate a program; interpreting or compiling.
2. there are a few basic operations most languages can perform:
 - input: Get data from the keyboard, or a file, or some other device.
 - output: Display data on the screen or send data to a file or other device.
 - math: Perform basic mathematical operations like addition and multiplication.
 - testing: Check for certain conditions and execute the appropriate sequence of statements.
 - repetition: Perform some action repeatedly, usually with some variation.

3. one way to describe programming is the process of breaking a large, complex task up into smaller and smaller subtasks until eventually the subtasks are simple enough to be performed with one of these basic operations.
4. There are a few different kinds of errors that can occur in a program:
 - Compile-time errors
 - Run-time errors
 - Logic errors and semantics

5. Formal and natural languages
 - Natural languages are the languages that people speak, like English, Spanish, and French. They were not designed by people (although people try to impose some order on them); they evolved naturally.
 - Formal languages are languages that are designed by people for specific appli- cations. For example, the notation that mathematicians use is a formal language that is particularly good at denoting relationships among numbers and symbols. Chemists use a formal language to represent the chemical structure of molecules. And most importantly:
 - Programming languages are formal languages that have been designed to express computations.

6. Syntax rules come in two flavors, pertaining to tokens and structure. 
 - Tokens are the basic elements of the language, like words and numbers and chemical elements.
 - The second type of syntax rule pertains to the structure of a statement; that is, the way the tokens are arranged.

7. Although formal and natural languages have many features in common—tokens, structure, syntax and semantics—there are many differences.
 - ambiguity: Natural languages are full of ambiguity, which people deal with by using contextual clues and other information. Formal languages are designed to be nearly or completely unambiguous, which means that any statement has exactly one meaning, regardless of context.
 - redundancy: In order to make up for ambiguity and reduce misunderstand- ings, natural languages employ lots of redundancy. As a result, they are often verbose. Formal languages are less redundant and more concise. 
 - literalness: Natural languages are full of idiom and metaphor. If I say, “The other shoe fell,” there is probably no shoe and nothing falling. Formal languages mean exactly what they say.

8. Programs: The meaning of a computer program is unambiguous and literal, and can be understood entirely by analysis of the tokens and structure. 

9. One of the most powerful features of a programming language is the ability to manipulate values through the use of variables.

10. ATTENTION: The older C89 standard allows variable declarations only at the beginning of a block of code. It is therefore necessary to put variable declarations before any other statements, even if the variable itself is only needed much later in your program.

11. Declaration adn Assignment
 - When you declare a variable, you create a named storage location.
 - When you make an assignment to a variable, you give it a value.
 - A variable is defined when the compiler allocates the storage for the variable.
 - A variable is declared when the compiler is informed that a variable exists (and this is its type); it does not allocate the storage for the variable at that point.

12. When both of the operands are integers (operands are the things operators operate on), the result must also be an integer, and by definition integer division always rounds down

13. the result of a comparison operator is a boolean, so you can store it in a variable(short evenFlag = (n%2 == 0);) 
14. all the things functions are good for:
 - By giving a name to a sequence of statements, you make your program easier to read and debug.
 - Dividing a long program into functions allows you to separate parts of the program, debug them in isolation, and then compose them into a whole.
 - Functions facilitate both recursion and iteration.
 - Well-designed functions are often useful for many programs. Once you write and debug one, you can reuse it.
