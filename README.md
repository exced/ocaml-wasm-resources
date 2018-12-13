# OCaml - WASM resources

From the [WebAssembly website](https://webassembly.org):

> WebAssembly (abbreviated Wasm) is a binary instruction format for a stack-based virtual machine. Wasm is designed as a portable target for compilation of high-level languages like C/C++/Rust, enabling deployment on the web for client and server applications.

## Road to WebAssembly

A good overview of the project:
[Sander Spies - Down the WebAssembly rabbit hole | ReasonConf 2018](https://www.youtube.com/watch?v=v4MHUbIWNZ8&frags=pl%2Cwn)

Walkthrough articles:

- [A WebAssembly backend for OCaml](https://medium.com/@sanderspies/a-webassembly-backend-for-ocaml-b78e7eeea9d5)

- [The road to WebAssembly GC for OCaml](https://medium.com/@sanderspies/the-road-to-webassembly-gc-for-ocaml-bd44dc7f9a9d).

What's left:

- Garbage Collector
- Tail calls
- Exceptions handling

## WebAssembly

Here are some documentations about WebAssembly.

A video to help you quickly understand WebAssembly:
[WebAssembly demystified by Jay Phelps](https://www.youtube.com/watch?v=6Y3W94_8scw&frags=pl%2Cwn)

Resources:

- [Official website](https://webassembly.org)
- [Specs proposals](https://github.com/WebAssembly)

If you want to deep dive here are some concepts you'll need to understand:

- [Linking](https://github.com/WebAssembly/tool-conventions/blob/master/Linking.md)
- [Garbage Collector](https://github.com/WebAssembly/gc)
- [Tail calls](https://github.com/WebAssembly/tail-call)
- [Exceptions](https://github.com/WebAssembly/exception-handling)

Semantics:
- [WebAssembly semantics (official doc)](https://webassembly.org/docs/semantics/)

## Understanding the OCaml compiler

A small understanding of the OCaml compiler might be required.

Here are some good resources from [Real World OCaml](https://dev.realworldocaml.org):

- [Memory Representation of Values](https://dev.realworldocaml.org/runtime-memory-layout.html)
- [Understanding the Garbage Collector](https://dev.realworldocaml.org/garbage-collector.html)
- [The Compiler Frontend: Parsing and Type Checking](https://dev.realworldocaml.org/compiler-frontend.html)
- [The Compiler Backend: Bytecode and Native code](https://dev.realworldocaml.org/compiler-backend.html)

## Getting started

You can find the resources from Sander Spies [here](https://github.com/SanderSpies/ocaml/tree/wasm-backend).

This branch is the most up-to-date and starts implementing a garbage collector and is WIP.

If you want to start without GC implementation, here is the
[branch](https://github.com/SanderSpies/ocaml/tree/before_gc).

And to help you out getting started, there is a [Docker repo](https://github.com/SanderSpies/ocaml-wasm-docker).

## Contact

There is a channel dedicated to wasm on the [OCaml discord](https://discordapp.com/invite/cCYQbqN).

## Notes

Special thanks to Sander Spies for his work on this project and for helping people onboarding and understanding it.
