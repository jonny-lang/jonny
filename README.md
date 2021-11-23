 # jonny-lang
 jonny is a stack based programming language

 also compiling jonny files __**currently**__ doesnt work on windows
 you can probably compile jonny files using wsl but idk

 ## roadmap
 jonny roadmap
 - [x] Compiled
 - [x] Native
 - [x] Stack-Based
 - [ ] Turing-Complete
 - [ ] Statically Typed
 - [ ] Self-Hosted

 ## quickstart

 ### simulation

 simulating jonny files simply interprets the program

 ```console
 $ ./jonny.py sim program.jonny
 ```

 ### compiling

 compiling jonny files generates assemble code and compiles it with [nasm](https://www.nasm.us/)

 ```console
 $ ./jonny.py com program.jonny
 $ ./program 
 ```