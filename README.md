# Assignment-8-COMP-302-SOLVED

Download Here: [Assignment 8 COMP 302 SOLVED](https://jarviscodinghub.com/assignment/assignment-8-comp-302-solved/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Question 1[50 points] In this question you will implement a parser for the language of
algebraic expressions described in class on the 11th of March. We use the following type
definition to capture expression trees:
type exptree = Var of char | Expr of char * exptree * exptree
The input will be just plain strings and the output has to be an exptree. The input strings
consist of simple algebraic expressions with + and * and one-character symbols that are
just lower-case letters. It is also possible to use parentheses in the input expressions. Blanks
are not allowed in the input1
. The parser itself will consist of three mutually recursive
functions as explained in class. There is a template installed in the LearnO’Caml system
with more details. I will put a file with examples on the course web page. I am interested
in making sure that the parser works correctly on valid input strings, I won’t worry about
dealing with bad strings and implementing error handling. I have not written the parser
to detect all the possible problems. In the file called examples.ml you will see that not all
bad strings are reported as bad strings, one simply gets the wrong parse tree. The most
complicated part is the recursive procedure called primary which I have written for you.
This is defined together with expr and term as three mutually recursive functions.
Question 2[50 points] In this question you will implement a toy code generator for the
very simple stack machine as explained in class on March 13th. Use the output from the
parser as input to the code generator. The code generator should just print the “machine
instructions”. Use statements like
Printf.printf “LOAD %c\n” c
Printf.printf “ADD %c\n” c
Printf.printf “MUL %c\n” c
Printf.printf “STORE %i\n” tempstore
Printf.printf “ADD %i\n” tempstore
within your program to get this effect.
1
If you want to do something fancier please do so on your own but do not submit it!

