This is 0x19. C - Stacks, Queues - LIFO, FIFO project.
* Author name: Luka Gatkuoth Nyuot

The learning objective of this project is:-
 * What do LIFO and FIFO mean
 * What is a stack, and when to use it
 * What is a queue, and when to use it
 * What are the common implementations of stacks and queues
 * What are the most common use cases of stacks and queue
 * What is the proper way to use global variables

The Monty language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

Monty byte code files

Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument:

Task # 0. push, pall
Implement the push and pall opcodes.

The push opcode
The opcode push pushes an element to the stack.

The pall opcode
The opcode pall prints all the values on the stack, starting from the top of the stack.

Task #1. pint
Implement the pint opcode.

Task #2. pop
Implement the pop opcode

Task #3. swap
Implement the swap opcode.

Task #4. add
Implement the add opcode

Task #5. nop
Implement the nop opcode.

Task #6. sub
Implement the sub opcode.

Task #7. div
Implement the div opcode.

Task #8. mul
Implement the mul opcode.

Task #9. mod
Implement the mod opcode.

Task #10. comments
Every good language comes with the capability of commenting. When the first non-space character of a line is #, treat this line as a comment (don’t do anything).

Task # 11. pchar
Implement the pchar opcode.

Task #12. pstr
Implement the pstr opcode.

Task #13. rotl
Implement the rotl opcode

Task #14. rotr
Implement the rotr opcode.

Task #15. stack, queue
Implement the stack and queue opcodes.

Task #16. Brainf*ck
Write a Brainf*ck script that prints School, followed by a new line.

All your Brainf*ck files should be stored inside the bf sub directory
You can install the bf interpreter to test your code: sudo apt-get install bf

Task #17. Add two digits
Add two digits given by the user.

Read the two digits from stdin, add them, and print the result
The total of the two digits with be one digit-long (<10)

Task #18. Multiplication
Multiply two digits given by the user.

Read the two digits from stdin, multiply them, and print the result
The result of the multiplication will be one digit-long (<10)

Task #19. Multiplication level up
Multiply two digits given by the user.
Read the two digits from stdin, multiply them, and print the result, followed by a new line
