
# Taro
> Written with [StackEdit](https://stackedit.io/).
### Taro is a small, dynamically typed scripting language. 
#### Note: This project is still currently under construction

A bytecode interpreter and virtual machine for my ML-inspired programming language that targets custom-made bytecode. Implements a Pratt-styled Precedence parser, implicit type assignment, and bytecode IR generation from a source file. Written in C.

```
let a = 5; 
let b = 25;

let c = "hello world";
print c;

print a == 5;
let d = [1, 2, 3];

print d[0];

```
Taro is designed to utilize the ease of readability of scripting languages similar to JavaScript and Python while maintaining other traditional syntax  considerations such as curly braces for scoping, and semicolons. 

Planned for the future is a garbage collector to automatically manage heap-allocated objects such as strings, and arrays. Within the next update I will have control flow, which will make Taro turing complete. Further down, I will be implementing OOP functionality.

