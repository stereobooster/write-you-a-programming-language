# Write you a programming language

> If you don't know how compilers work, then you don't know how computers work.
>
> -- [Steve Yegge](http://steve-yegge.blogspot.com/2007/06/rich-programmer-food.html)

> If you can’t explain something in simple terms, you don’t understand it
>
> -- [Somebody smart](https://skeptics.stackexchange.com/questions/8742/did-einstein-say-if-you-cant-explain-it-simply-you-dont-understand-it-well-en)

> Dr. Hoenikker used to say that any scientist who couldn't explain to an eight-year-old what he was doing was a charlatan.
>
> -- Kurt Vonnegut, Cat's Cradle (said by Dr. Asa Breed; chapter 15)

List of small programming languages that you can implement in a relatively small amount of time for educational purposes.

- [Make a Lisp](https://github.com/kanaka/mal) - Clojure inspired Lisp interpreter implemented in 82 languages (85 different implementations and 105 runtime modes)
- [The Programming Languages Zoo](https://plzoo.andrej.com/) is a collection of miniature programming languages which demonstrates various concepts and techniques used in programming language design and implementation
- [Write you a Haskell](http://dev.stephendiehl.com/fun/). We will build a small functional language called Fun which is a partial Haskell 2010 toy language; complete with a parser, type inference, datatypes, pattern matching, desugaring, typeclasses, higher-kinded types, monadic IO, arbitrary-rank polymorphism, records, Core language, STG intermediate language, lazy evaluation, interpreter, native code generator, a runtime, and several optimization passes.
- [Duet](https://github.com/chrisdone/duet) - A tiny language, a subset of Haskell (with type classes) aimed at aiding teachers teach Haskell
- [Implementing a JIT Compiled Language with Haskell and LLVM](https://www.stephendiehl.com/llvm/). This tutorial runs through the implementation of a simple language, and the basics of how to build a compiler in Haskell, showing how fun and easy it can be
- [How to implement a programming language in JavaScript](http://lisperator.net/pltut/dream). This is a tutorial on how to implement a programming language. If you ever wrote an interpreter or a compiler, then there is probably nothing new for you here. But, if you're using regexps to “parse” anything that looks like a programming language, then please read at least the section on parsing.
- [Monkey](https://github.com/prologic/monkey-lang) programming language interpreter designed in "Writing An Interpreter In Go". A step-by-step walk-through where each commit is a fully working part
- [Create Your Own Programming Language with Rust](https://createlang.rs/intro.html). This book arises from my frustration of not finding modern, clear and concise teaching materials that are readily accessible to beginners like me who wants to learn a bit on how to create their own programming language.
- [Crafting interpreters](http://www.craftinginterpreters.com/contents.html). This is a book on implementing interpreters for programming languages.
  - [Dictu](https://github.com/dictu-lang/Dictu)
- [Write Yourself a Scheme in 48 Hours](https://upload.wikimedia.org/wikipedia/commons/a/aa/Write_Yourself_a_Scheme_in_48_Hours.pdf). An Introduction to Haskell through Example
  - [zepto](https://github.com/zepto-lang/zepto)
- [Bril](https://github.com/sampsyo/bril): A Compiler Intermediate Representation for Learning

## Lisps

- [(How to Write a (Lisp) Interpreter (in Python))](http://www.norvig.com/lispy.html). This page has two purposes: to describe how to implement computer language interpreters in general, and in particular to build an interpreter for most of the Scheme dialect of Lisp using Python 3 as the implementation language.
- [(An ((Even Better) Lisp) Interpreter (in Python))](http://norvig.com/lispy2.html). In a previous essay I showed how to write a simple Lisp interpreter in 90 lines of Python: lis.py. In this essay I make the implementation, lispy.py, three times more complicated, but more complete.
- [Lisp implementations](https://bernsteinbear.com/blog/lisp/). Compiling a Lisp. Writing a Lisp.
- [Building LISP](https://www.lwh.jp/lisp/). The best way to understand how something works is to try to build it for yourself. Reading somebody else's explanation might satisfy your curiosity, but without the experience of falling into all the little traps it is difficult to get a feel for why something is designed a certain way.
- [Build Your Own Lisp](http://buildyourownlisp.com/) - Learn C and build your own programming language in 1000 lines of code!

## Type systems

- [Cubiml](https://github.com/Storyyeller/cubiml-demo) is a simple ML-like programming language with subtyping and full type inference. You can try it out online in your browser here. Cubiml is not intended to be used in its own right, but rather to serve as a tutorial for implementing cubic biunification, and therefore has a deliberately minimal feature set.
- [Tiny OutsideIn(X)](https://github.com/Jaak/TinyOutsideIn). This is a simple reference implementation of OutsideIn(X) type inference algorithm.
- [Elaboration zoo](https://github.com/AndrasKovacs/elaboration-zoo). This repo includes a series of Haskell implementations for elaborating dependently typed languages, where packages add progressively more power and functionality. Currently, packages focus on basics of unification, inference and implicit argument handling, and we don't have any inductive types or modules (yet).
## Related

- [awesome-compilers: tutorials](https://github.com/aalhour/awesome-compilers#tutorials)
- [A Bestiary of Single-File Implementations of Programming Languages](https://github.com/marcpaq/b1fipl)
- [Programming languages and paradigms lecture](https://github.com/zporky/langs-and-paradigms)
