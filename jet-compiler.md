JetCompiler

* JetCompiler is embedded with JetPM
  * includeSources includes either a directory or a file by each element
  * Git and file: dependencies are supported
* Compile-time verification phase of each production is similiar to ActionScript 3 and ECMA-357 2nd edition (E4X)
* JetCompiler should be flexible for allowing other compilers to be built on top of it.
  * File extensions to recognize
  * File processor for non .jet files
* Generator of Jet bytecode that simplifies the AST and semantics into a low-level format that is easy to parse, using a jump control flow and stack values as in AVM2

JetPM registry

* Platforms are associated with a compiler binary to use (the subset of JetCompiler)
