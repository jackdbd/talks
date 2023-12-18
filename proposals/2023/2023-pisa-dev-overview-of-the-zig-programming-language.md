# Panoramica su Zig

## Language

Italian

## Status

Accepted

## Length

60 minutes

## Audience level

Intermediate

## Tags / Keywords

- programming-language
- zig

## Description

Zig is a modern programming language that focuses on simplicity and explicitness.

It has no preprocessor and no macros black magic. Memory management is manual, so you are the only one responsible for memory allocations in your application. Error handling is simple and predictable.

Zig has a build system that you would expect from a modern programming language, and you can use it to compile for x86_64, ARM, WASM and many more architectures. You can even use the zig toolchain to compile C code.

One of the best features of Zig is its exceptional C interop: you can start writing Zig today and use it in your C codebase; you can also wrap an existing C library in a Zig wrapper, so you can gradually transition your codebase from C to Zig.

## Pre-requisites

Interest in native languages (e.g. C, Rust). Some knowledge on how memory is allocated in stack-based architectures.

## Outline

- How to install Zig
- How to setup VS Code for Zig development
- Overview of the syntax: costants and variables, arrays, slices, control structures, loops, functions, error handling
- Build system: build.zig and build modes
- manual memory management, overview of the most used memory allocators, how to implement a custom memory allocator
- Zig arrays vs slices
- overview of the Zig standard library
- Zig build system
- Zig / C interop: wrap a C library with Zig, consume a Zig library in C
- ditch GCC and Clang for zig cc
- overview of advanced topics: metaprogramming with comptime, async and await in Zig
- compile for wasm and run in a wasm runtime (browser, Node.js WASI)
- overview of a few exciting projects made with Zig: BPF, zig-v8, Zig-PSPS, CosmicJS, bun, Zig for embedded systems, game engines in Zig

## Social media post

