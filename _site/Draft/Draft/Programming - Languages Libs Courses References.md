###Programming Language Courses and References



TOC
Cull
ASM
C/C++
Go
Java
.Net
Perl
Powershell
Python



###Cull



[Secure Coding Standards - Android](https://www.securecoding.cert.org/confluence/pages/viewpage.action?pageId=111509535)




[Secure Coding Standards - Android](https://www.securecoding.cert.org/confluence/pages/viewpage.action?pageId=111509535)


[What a C programmer should know about memory](http://marek.vavrusa.com/c/memory/2015/02/20/memory/)


[x86 Assembly Guide/Reference - Wikibooks](https://en.wikibooks.org/wiki/X86_Assembly)
* Introduction for those who don�t know ASM and a reference for those that do.





[Slides - Weird - Machine Motivated Practical Page Table Shellcode & Finding Out What's Running on Your System](https://www.defcon.org/images/defcon-22/dc-22-presentations/Macaulay/DEFCON-22-Shane-Macaulay-Weird-Machine-Motivated-Practical-Page-Table-Shellcode-UPDATED.pdf) 



###General





###Assembly x86/x64/ARM

####Tutorials


[Guide to x86 Assembly](http://www.cs.virginia.edu/~evans/cs216/guides/x86.html)

[Intro to x86 calling conventions](http://codearcana.com/posts/2013/05/21/a-brief-introduction-to-x86-calling-conventions.html)

[Reading ASM](http://cseweb.ucsd.edu/classes/sp11/cse141/pdf/02/S01_x86_64.key.pdf)

[Machine-Level Representation of Programs](https://2013.picoctf.com//docs/asmhandout.pdf)



####Courses


http://opensecuritytraining.info/IntroX86.html

####Reference

[Nasm x86 reference](https://www.cs.uaf.edu/2006/fall/cs301/support/x86/)

[x86 Assembly Guide/Reference - Wikibooks](https://en.wikibooks.org/wiki/X86_Assembly)
* Introduction for those who don�t know ASM and a reference for those that do.


[x86 Disassembly/Calling Conventions](https://en.wikibooks.org/wiki/X86_Disassembly/Calling_Conventions)
[x86 Disassembly/Calling Convention Examples](https://en.wikibooks.org/wiki/X86_Disassembly/Calling_Convention_Examples)

[Walkthrough: Creating and Using a Dynamic Link Library (C++)](https://msdn.microsoft.com/en-us/library/ms235636.aspx)



###Source Code Analysis


[RIPS]http://rips-scanner.sourceforge.net/)
* RIPS is a tool written in PHP to find vulnerabilities in PHP applications using static code analysis. By tokenizing and parsing all source code files RIPS is able to transform PHP source code into a program model and to detect sensitive sinks (potentially vulnerable functions) that can be tainted by user input (influenced by a malicious user) during the program flow. Besides the structured output of found vulnerabilities RIPS also offers an integrated code audit framework for further manual analysis. 



###Videos

[Introduction Video Series(6) to x86 Assembly](https://www.youtube.com/watch?v=qn1_dRjM6F0&list=PLPXsMt57rLthf58PFYE9gOAsuyvs7T5W9)


###Papers

[Mov is turing complete](http://www.cl.cam.ac.uk/~sd601/papers/mov.pdf)


###C

[Stanford C 101](http://cslibrary.stanford.edu/101/EssentialC.pdf)
* Stanford CS Education Library: A 45 page summary of the C language. Explains all the common features and techniques for the C language. The coverage is pretty quick, so it is most appropriate for someone with some programming background who needs to see how C works. Topics include variables, int types, floating point types, promotion, truncation, operators, control structures (if, while, for), functions, value parameters, reference parameters, structs, pointers, arrays, the pre-processor, and the standard C library functions. (revised 4/2003) 
[Homepage](http://cslibrary.stanford.edu/101/)


[Stanford C Pointers and Memory](http://cslibrary.stanford.edu/102/PointersAndMemory.pdf)
* Stanford CS Education Library: a 31 page introduction to programming with pointers and memory in C, C++ and other languages. Explains how pointers and memory work and how to use them -- from the basic concepts through all the major programming techniques. Can be used as an introduction to pointers for someone with basic programming experience or as a quick review. Many advanced programming and debugging problems only make sense with a solid understanding of pointers and memory -- this document tries to provide that understanding. 
* [Homepage](http://cslibrary.stanford.edu/102/)



###Python
[Hachoir](https://bitbucket.org/haypo/hachoir/wiki/Home)
* Hachoir is a Python library that allows to view and edit a binary stream field by field

[Python Library for interacting with Serial Ports](http://pyserial.sourceforge.net/)

[Understanding Python Bytecode](http://security.coverity.com/blog/2014/Nov/understanding-python-bytecode.html)

[Obfuscating python](https://reverseengineering.stackexchange.com/questions/1943/what-are-the-techniques-and-tools-to-obfuscate-python-programs)

[Equip: python bytecode instrumentation](https://github.com/neuroo/equip)
* equip is a small library that helps with Python bytecode instrumentation. Its API is designed to be small and flexible to enable a wide range of possible instrumentations. The instrumentation is designed around the injection of bytecode inside the bytecode of the program to be instrumented. However, the developer does not need to know anything about the Python bytecode since the injected code is Python source.



###Perl

[Introduction to Perl](http://www.perl.com/pub/2000/10/begperl1.html)



###Powershell


Try/Catch Exception in Powershell
"""

try {
#stuff
} catch {
$ErrorMessage = $_.Exception.Message
$ErrorSource = $_.Exception.Source
$err = $ErrorSource + " reports: " + $ErrorMessage
}

"""



###Useful Libraries/programs

[Shellpaste](https://github.com/andrew-morris/shellpaste)
* Tiny snippet of code that pulls ASCII shellcode from pastebin and executes it. The purpose of this is to have a minimal amount of benign code so AV doesn't freak out, then it pulls down the evil stuff. People have been doing this kind of stuff for years so I take no credit for the concept. That being said, this code (or similar code) works surprisingly often during pentests when conventional malware fails. 
