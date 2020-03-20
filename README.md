# About

VS Code addon providing language support for the P3 Assembly programming language, the language used in the fictitious [P3 processor](http://algos.inesc-id.pt/arq-comp/?Material_Did%C3%A1tico___Processador_P3), created at IST (Instituto Superior Técnico) for educational purposes.

## Features

+ Syntax highlighting (different themes will render different colors): recognizes all of P3's instruction mnemonics, labels and addressing modes;
+ Hover documentation: put your mouse over an instruction or register to see its documentation and usage
+ Constant convertion: put your mouse over a constant to see its binary, hex, decimal and ascii values.
+ Constant declaration features: jump to constants/variables definition (right click > definition or command/control+click)
+ Label declaration features: jump to a label's position on the source code (on CALL, BR and JMP instructions)

## Credits

+ The logo design was created by *António Luciano*.
+ The #constants and labels definitions for the syntax were taken [from this extension](https://github.com/13xforever/x86_64-assembly-vscode).
+ Borrowed heavily from [this extension](https://github.com/prb28/vscode-amiga-assembly).
+ Special thanks to *José Neves* for copy pasting all of instructions' documentation