# Write you a programming language

List of small programming languages that you can implement in a relatively small amount of time for educational purposes.

| Host                                                                                              | Language      | Type                  | Target      | Features                                                                                     |
| ------------------------------------------------------------------------------------------------- | ------------- | --------------------- | ----------- | -------------------------------------------------------------------------------------------- |
| [(many)](https://github.com/kanaka/mal)                                                           | Lisp (MAL)    | Interpreter           | -           | TCO, macros, bootstrapping                                                                   |
| [Assembly](https://github.com/nornagon/jonesforth/blob/master/jonesforth.S)                       | Forth         | Compiler              |             |                                                                                              |
| [C](https://github.com/lotabout/write-a-C-interpreter)                                            | C             | Interpreter           | -           | no parser generator, bootstrapping                                                           |
| [C](https://github.com/lotabout/Let-s-build-a-compiler)                                           | LBaC          | Compiler              | x86         |                                                                                              |
| [C](https://github.com/DoctorWkt/acwj)                                                            | C(SubC)       | Compiler              | Assembly    |                                                                                              |
| [C](http://www.t3x.org/subc/j)                                                                    | C(SubC)       | Compiler              | x86-64      | It can compile itself and passes gcc -Wall -pedantic                                         |
| [C](http://buildyourownlisp.com/contents)                                                         | Lisp          | Interpreter           | -           | macros                                                                                       |
| [C](https://www.lwh.jp/lisp/)                                                                     | Lisp          | Interpreter           | -           | macros, TCO, continuations, GC                                                               |
| [C](https://github.com/rui314/minilisp)                                                           | Lisp          | Interpreter           | -           | GC                                                                                           |
| [C](https://carld.github.io/2017/06/20/lisp-in-less-than-200-lines-of-c.html)                     | Lisp          | Interpreter           | -           | Lisp In Less Than 200 Lines Of C                                                             |
| [C](https://github.com/rui314/chibicc)                                                            | C             | Compiler              |             |                                                                                              |
| [C](http://people.delphiforums.com/gjc//siod.html)                                                | Scheme        | Interpreter           | -           | GC                                                                                           |
| [C](http://peter.michaux.ca/index#Scheme)                                                         | Scheme        | Interpreter           | -           |                                                                                              |
| [C](http://oldblog.antirez.com/page/picol.html)                                                   | TCL           | Interpreter           | -           | a Tcl interpreter in 550 lines of C code                                                     |
| [C++](https://llvm.org/docs/tutorial/MyFirstLanguageFrontend/index.html)                          | Kaleidoscope  | Compiler, Interpreter | LLVM        | procedural language that allows you to define functions, use conditionals, math, JIT         |
| [C++](https://gnuu.org/2009/09/18/writing-your-own-toy-compiler/), Flex, Bison                    | C-like        | Compiler              | LLVM        |                                                                                              |
| [C++](http://howtowriteaprogram.blogspot.com/2010/11/lisp-interpreter-in-90-lines-of-c.html)      | Lisp          | Interpreter           | -           | interpreter in 90 lines of C++                                                               |
| [Go](https://github.com/qeedquan/gosubcj)                                                         | C(SubC)       | Compiler              | x86-64      | It can compile itself and passes gcc -Wall -pedantic                                         |
| [Haskell](https://github.com/chrisdone/duet), parsec                                              | Haskell(Duet) | Interpreter           | -           | type classes, non-strict, but is not lazy                                                    |
| [Haskell](https://www.stephendiehl.com/llvm/), parsec                                             | Kaleidoscope  | Compiler              | LLVM        | procedural language that allows you to define functions, use conditionals, math, JIT         |
| [Haskell](https://en.wikibooks.org/wiki/Write_Yourself_a_Scheme_in_48_Hours), Parsec              | Scheme        | Interpreter           | -           |                                                                                              |
| [Haskell](https://www.wespiser.com/writings/wyas/home.html), Parsec                               | Scheme        | Interpreter           | -           |                                                                                              |
| [Haskell](https://g-ford.github.io/cradle/)                                                       | LBaC          | Compiler              |             |                                                                                              |
| [Idris](https://github.com/edwinb/SPLV20)                                                         | TinyIdris     |                       |             | typechecking, evaluation, unification ([video](https://www.youtube.com/watch?v=2pa3oRFNO8E)) |
| [Java](http://jakubdziworski.github.io/categories.html#Enkel-ref)                                 | Enkel         | Compiler              | JVM         |                                                                                              |
| [Java](http://www.craftinginterpreters.com/)                                                      | Lox           | Interpreter           | -           |                                                                                              |
| [JavaScript](http://lisperator.net/pltut/dream), parsec                                           | λanguage      | Compiler              | JavaScript  |                                                                                              |
| [JavaScript](https://github.com/keyanzhang/the-super-tiny-interpreter), babylon                   | JavaScript    | Interpreter           | -           |                                                                                              |
| [JavaScript](https://maryrosecook.com/blog/post/little-lisp-interpreter)                          | Lisp          | Interpreter           | -           | The code is 116 lines                                                                        |
| [OCaml](https://plzoo.andrej.com/), menhir                                                        | miniml        | Compiler, Interpreter | Abstract    | eager, functional, recursive functions, statically typed, compiler, abstract machine         |
| [OCaml](https://plzoo.andrej.com/), menhir                                                        | miniml_error  | Compiler, Interpreter | Abstract    | like miniml that can also abort execution                                                    |
| [OCaml](https://plzoo.andrej.com/), menhir                                                        | minihaskell   | Interpreter           | -           | lazy, functional, integers, booleans, lists, recursion, statically typed                     |
| [OCaml](https://plzoo.andrej.com/), menhir                                                        | miniprolog    | Interpreter           | -           | logic programming, Horn clauses, unification                                                 |
| [OCaml](https://plzoo.andrej.com/), menhir                                                        | levy          | Interpreter           | -           | call-by-push value, statically typed                                                         |
| [OCaml](https://plzoo.andrej.com/), menhir                                                        | comm          | Compiler              | Abstract    | a simple procedural langauge                                                                 |
| [OCaml](https://plzoo.andrej.com/), menhir                                                        | calc          | Interpreter           | -           | integer arithmetic                                                                           |
| [OCaml](https://plzoo.andrej.com/), menhir                                                        | sub           | Interpreter           | -           | an eager purely functional language, mutable records, statically typed, subtyping            |
| [OCaml](https://plzoo.andrej.com/), menhir                                                        | boa           | Interpreter           | -           | object-oriented, eager, first-class functions, dynamic types, extensible objects             |
| [OCaml](https://plzoo.andrej.com/), menhir                                                        | lambda        | Interpreter           | -           | untyped λ-calculus, several evaluation strategies                                            |
| [OCaml](https://plzoo.andrej.com/), menhir                                                        | poly          | Interpreter           | -           | lazy, functional, statically typed, parametric polymorphism, type inference                  |
| [OCaml](https://bernsteinbear.com/blog/lisp/00_fundamentals/)                                     | Lisp          | Interpreter           | -           |                                                                                              |
| [OCaml](https://norasandler.com/2017/11/29/Write-a-Compiler.html)                                 | C             | Compiler              | x86         |                                                                                              |
| [Python](http://www.norvig.com/lispy.html)                                                        | Lisp          | Interpreter           | -           | Lisp interpreter in 90 lines of Python                                                       |
| [Python](http://aosabook.org/en/500L/a-python-interpreter-written-in-python.html)                 | Python        | Interpreter           | -           | Python interpreter fits easily into the 500-line size restriction                            |
| [Python](https://ruslanspivak.com/lsbasi-part1/)                                                  |               | Interpreter           | -           |                                                                                              |
| [Python](http://khamidou.com/compilers/lisp.py/)                                                  | Lisp          | Interpreter           | -           |                                                                                              |
| [Racket](https://beautifulracket.com/)                                                            |               |                       |             |                                                                                              |
| [Ruby](https://www.destroyallsoftware.com/screencasts/catalog/a-compiler-from-scratch)            |               | Compiler              |             |                                                                                              |
| [Ruby](https://blog.beezwax.net/2017/07/07/writing-a-markdown-compiler/)                          | Markdown      | Compiler              | HTML        |                                                                                              |
| [Ruby](http://hokstad.com/compiler)                                                               | Ruby          | Compiler              |             |                                                                                              |
| [Scheme](http://matt.might.net/articles/metacircular-evaluation-and-first-class-run-time-macros/) | Scheme        | Interpreter           | -           | First-class (run-time) macros and meta-circular evaluation                                   |
| [Scheme](http://matt.might.net/articles/compiling-scheme-to-c/)                                   | Scheme        | Compiler              | C           | Compiling Scheme to C with closure conversion                                                |
| [Scheme](http://matt.might.net/articles/compiling-to-java/)                                       | Scheme        | Compiler              | Java        |                                                                                              |
| [Swift](https://www.uraimo.com/2017/02/05/building-a-lisp-from-scratch-with-swift/)               | Lisp          | Interpreter           | -           |                                                                                              |
| [Turbo Pascal 4.0](https://compilers.iecc.com/crenshaw/)                                          | LBaC          | Compiler              | x8086       |                                                                                              |
| [TypeScript](https://blog.scottlogic.com/2019/05/17/webassembly-compiler.html)                    |               | Compiler              | WebAssembly |                                                                                              |
| 🚧 [C](https://bernsteinbear.com/blog/compiling-a-lisp-0/)                                        | Lisp          | Compiler              |             |                                                                                              |
| 🚧 [Haskell](http://dev.stephendiehl.com/fun/)                                                    | Haskell(fun)  |                       |             |                                                                                              |

## Type systems

- [Cubiml](https://github.com/Storyyeller/cubiml-demo) is a simple ML-like programming language with subtyping and full type inference. You can try it out online in your browser here. Cubiml is not intended to be used in its own right, but rather to serve as a tutorial for implementing cubic biunification, and therefore has a deliberately minimal feature set.
- [Tiny OutsideIn(X)](https://github.com/Jaak/TinyOutsideIn). This is a simple reference implementation of OutsideIn(X) type inference algorithm.
- [Elaboration zoo](https://github.com/AndrasKovacs/elaboration-zoo). This repo includes a series of Haskell implementations for elaborating dependently typed languages, where packages add progressively more power and functionality. Currently, packages focus on basics of unification, inference and implicit argument handling, and we don't have any inductive types or modules (yet).

## Courses & Books

- [Programming languages and paradigms lecture](https://github.com/zporky/langs-and-paradigms)
- [Programming languages](https://opendsa.cs.vt.edu/ODSA/Books/PL/html/index.html)
- [An Incremental Approach to Compiler Construction](http://scheme2006.cs.uchicago.edu/11-ghuloum.pdf) by Abdulaziz Ghuloum. Writing a Compiler in 24 Small Steps.
- [A Simple Scheme Compiler](https://www.cs.utexas.edu/ftp/garbage/cs345/schintro-v14/schintro_142.html#SEC271)
- [CS 4410/6410: Compiler Design](https://course.ccs.neu.edu/cs4410sp20/#%28part._lectures%29_)

## Related

- [awesome-compilers: tutorials](https://github.com/aalhour/awesome-compilers#tutorials)
- [Build your own Programming Language](https://github.com/danistefanovic/build-your-own-x#build-your-own-programming-language)
- [A Bestiary of Single-File Implementations of Programming Languages](https://github.com/marcpaq/b1fipl)
- [Programming languages resources](https://bernsteinbear.com/pl-resources/)
- [nanopass](http://nanopass.org/index.html). Clean Compiler Creation Language
- [Bril](https://github.com/sampsyo/bril): A Compiler Intermediate Representation for Learning

## Quotes

Most likely you will find one of those quotes in tutorials

> If you don't know how compilers work, then you don't know how computers work.
>
> -- [Steve Yegge](http://steve-yegge.blogspot.com/2007/06/rich-programmer-food.html)

> If you can’t explain something in simple terms, you don’t understand it
>
> -- [Somebody smart](https://skeptics.stackexchange.com/questions/8742/did-einstein-say-if-you-cant-explain-it-simply-you-dont-understand-it-well-en)

> Dr. Hoenikker used to say that any scientist who couldn't explain to an eight-year-old what he was doing was a charlatan.
>
> -- Kurt Vonnegut, Cat's Cradle (said by Dr. Asa Breed; chapter 15)

> What I cannot create, I do not understand.
>
> -- Richard Feynman
