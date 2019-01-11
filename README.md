# protobuf-c-win
Protobuf-c Win-platform binaries, built with MSYS2, test on STM32F446 (IDE: Keil5).

Using https://github.com/protobuf-c/protobuf-c.

## How to use gen.exe?

1. Open a terminal.
2. Type `gen --help`.
3. OK! Now you know HOW.

## How to compile with Keil5?

1. Add **protobuf-c** folder to your project.
2. Generate your files use **gen.exe**, then add them to your project.
3. Write your program, according to files in **test** folder.
4. **DO NOT USE** **MicroLib**.

