# lecture 1.1<br>
📚**❔ what is programmig language ❔**\
  *language -- language is a medium of communication between 2 entities .*\
  **programming language** - language that helps to communicate between humans and computers.

### 📚low level language 
_Low-level language woh language hoti hai jo hardware ke bahut paas hoti hai.
Computer ko directly samajh aati hai, lekin humans ke liye difficult hoti hai._
Traditionally (in the early days), programmers used low-level languages to write programs.
- Low-level languages are very close to computer hardware.
- They are machine-dependent.
- They are difficult for humans to read and write.
- They provide very little abstraction from hardware.\
[low level diagram](image/the.png)

**why low level language are not optimal to use ❔**\
-->how low level language works :\
low level language directly talks to computers so the problems are:\
1.```Difficult to Understand :``` Written in binary or assembly so it is Hard for humans to read and write and Requires deep hardware knowledge\
2.```Machine Dependent :``` Code written for one CPU won’t run on another\
  Example: x86 vs ARM \
3.```Hard to Debug & Maintain :```
- Small mistake → program crash
- Debugging is complex
- Maintenance takes more time
4. ```Time-Consuming Development :``` Writing code takes longer because Every instruction must be managed manually
5. ```No Portability :```Cannot easily move program between systems .Must rewrite code for each architecture
6. Limited Abstraction
- Programmer must manage:
  - Memory
  - Registers
  - hardware resources
- Increases chances of errors

🧠 to overcome this we need a language which follows some rule of abstraction

### 📚Rules ofAbstraction:
1. assiging values to named variable
2. conditional execution (if else block)
3. iteration(loops)
4. Functions/procedures, recursion
5. aggregate data structure(a process that compiles and organizes large datasets into useful insights)-- list, arrays, dictionary
- we know modern programming language like python,java etc follows all these rules like they have loops,conditional statements. This makes these programming language more compfy to humans .\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; but now problem is that computer dosenot understand these high level programming langauge ...to sort this problem we had compiler and interpreter.

**compiler vs interpreter :**
|Feature	|Compiler	|Interpreter|
|--------|---------|-----------|
|**Translation**(converting a program written in one language into another language that the computer can understand)|	Whole program at once|	Line by line|`
|**Execution**(Execution means running the translated program so that the computer actually performs the instructions.)|	After compilation|	During translation
|Error handling|	Shows all errors together|	Stops at first error|
|Speed	|Faster execution|	Slower execution|
|Output| file	Generates executable| not any file generates|
|Memory|	More (stores object code)|	Less|
|Portability	|Less(same code maynot be run on multiple compiler)|	More(same code can run on multiple compiler)|
|Example|java,c++,c etc|python|


### ⚖️ Python vs java
**🧠Python Execution Flow**
```text
Python source (.py)
      ↓
Python Interpreter
      ↓
Platform-specific execution
```
**Key points:**
- Python code is not compiled into machine code
- Same .py file runs on:
  - Windows
  - Linux
  - macOS
- You only need a Python interpreter for that OS
- 👉 Source code portability

**🧠Java Execution Flow**
```text
Java source (.java)
      ↓
Java Compiler
      ↓
Bytecode (.class)
      ↓
JVM
      ↓
Machine
```
**Key points:**
- Java source → bytecode
- Bytecode is platform-independent
- JVM handles OS/CPU differences
- 👉 Bytecode portability
