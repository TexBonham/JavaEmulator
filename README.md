# JavaEmulator
 
A JVM bytecode interpreter written in C# (summer 2022). It parses compiled Java
`.class` files and executes their bytecode directly in a C# console application.
 
**Scope:** core bytecode execution up to classes and structs. Built as a learning
project to understand the JVM's execution model — class file structure, the operand
stack, and instruction dispatch — by implementing it from the specification rather
than reading about it.
 
**Status:** complete and archived. This project (together with
[Custom-Computer-Architecture](../../../Custom-Computer-Architecture)) was an early
step in a series of emulation and language projects that led to
[CishCompiler](../../../CishCompiler) (a compiler targeting .NET CIL) and
[CSharpOS](../../../CSharpOS) (a full OS emulator on a custom ISA).
