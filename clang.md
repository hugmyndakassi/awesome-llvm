# Awesome Clang [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This doc was forked from https://github.com/ingve/awesome-clang. However I prefer a monorepo for both LLVM and Clang; so I moved here.

# Pages
- Project site: http://clang.llvm.org, and [its doxygen docs](https://clang.llvm.org/doxygen/index.html)
- [Mailing List: cfe-dev](http://lists.cs.uiuc.edu/mailman/listinfo/cfe-dev)
- [Clang @ StackOverflow](http://stackoverflow.com/questions/tagged/clang)
- [Clang @ reddit](https://www.reddit.com/r/Clang/)
- [Clang @ GitHub](https://github.com/topics/clang)


## Tools

- [clang-check](http://clang.llvm.org/docs/ClangCheck.html) - Error checking and AST dumping based on [LibTooling](http://clang.llvm.org/docs/LibTooling.html)
- [scan-build](http://clang-analyzer.llvm.org/) - Clang Static Analyzer
- [scan-view](http://clang-analyzer.llvm.org/) - Clang Static Analysis Viewer
- ~~[clang-modernize](http://clang.llvm.org/extra/clang-modernize.html) - Modernize C++ code~~
- [clang-tidy](http://clang.llvm.org/extra/clang-tidy.html) - [Lint-like checks and beyondslides](http://llvm.org/devmtg/2014-04/PDFs/Talks/clang-tidy%20LLVM%20Euro%202014.pdf)
- [clangd](https://clangd.llvm.org/) - clangd language server (for [LSP](https://microsoft.github.io/language-server-protocol/))

### [clang-format](http://clang.llvm.org/docs/ClangFormat.html)

- [clang-format docs](https://clang.llvm.org/docs/ClangFormat.html) - A tool to format C/C++/Java/JavaScript/Objective-C/Protobuf code.
- [style options](https://clang.llvm.org/docs/ClangFormatStyleOptions.html) - clang-format style options.
- [configurator](https://zed0.co.uk/clang-format-configurator/) -  clang-format configurator.

### clang-tidy

- [clang-tidy](https://clang.llvm.org/extra/clang-tidy/) - clang-based C++ linter tool.
- [List of clang-tidy checks](https://clang.llvm.org/extra/clang-tidy/checks/list.html)
- [Writing a basic clang static analysis check](https://bbannier.github.io/blog/2015/05/02/Writing-a-basic-clang-static-analysis-check.html)

## pp-trace

- [pp-trace](https://clang.llvm.org/extra/pp-trace.html) - tool that traces preprocessor activity.


## clangd
- [CppCon 2018 -- Clangd: architecture of a scalable C++ language server](https://www.youtube.com/watch?v=5HIyAXj1YNQ)

## scan-build

### Clang static analyzer

- [Clang Static Analyzer](https://clang-analyzer.llvm.org/index.html) - a source code analysis tool that finds bugs in C, C++, and Objective-C programs.
- [scan-build](https://clang-analyzer.llvm.org/scan-build.html) -Running the analyzer from the command line.
- [Static Analysis with clang](https://btorpey.github.io/blog/2015/04/27/static-analysis-with-clang/)
- [CodeChecker](https://github.com/Ericsson/codechecker) - defect database and viewer extension for Clang Static Analyzer.
- [clang-analyzer-guide](https://github.com/haoNoQ/clang-analyzer-guide) An easy guide to Clang Static Analyzer extension.

### AddressSanitizer

- [AddressSanitizer](https://clang.llvm.org/docs/AddressSanitizer.html) - a fast memory error detector.
- [Address Sanitizer](https://www.mikeash.com/pyblog/friday-qa-2015-07-03-address-sanitizer.html) - overview by Mike Ash.

### Other Clang-based tools
- [Checked C](https://github.com/microsoft/checkedc) - an extension to C that lets programmers write C code that is guaranteed by the compiler to be type-safe
- [C++ Insights](https://github.com/andreasfertig/cppinsights) - a clang-based tool which does source to source transformation. Its goal is it to make things visible which normally, and intentionally, happen behind the scenes. [Live/online demo](https://cppinsights.io/) available.
- [CodeChecker](https://github.com/Ericsson/codechecker) - an analyzer tooling, defect database and viewer extension for the Clang Static Analyzer and Clang Tidy
- [Clang Power Tools](https://github.com/Caphyon/clang-power-tools) - Visual Studio extension with Clang/LLVM tools (`clang++`, `clang-tidy` and `clang-format`).
- [rtags](https://github.com/Andersbakken/rtags) - A c/c++ client/server indexer for c/c++/objc[++]
- [llvm-clang-samples](https://github.com/eliben/llvm-clang-samples) - Examples of LLVM and Clang written by Dr. [Eli Bendersky](http://eli.thegreenplace.net/)
- [srg-llvm-pass-tutorial](https://github.com/delcypher/srg-llvm-pass-tutorial) - A tutorial about llvm passes from [Software reliability group](http://srg.doc.ic.ac.uk/)
- [clang-llvm-tutorial](https://github.com/lijiansong/clang-llvm-tutorial) - clang & llvm examples
- [CodeChecker](https://codechecker.readthedocs.io/en/latest/) - a static analysis infrastructure built on the LLVM/Clang Static Analyzer toolchain for MacOS/Linux
- [Bear](https://github.com/rizsotto/Bear) - A tool that generates a compilation database for clang tooling
- [compiledb](https://github.com/nickdiego/compiledb) -- Tool for generating Clang's JSON Compilation Database files for *make-based* build systems.
- [lsif-clang](https://github.com/sourcegraph/lsif-clang) - Language Server Indexing Format (LSIF) generator for C, C++ and Objective C
- [codebrowser](https://github.com/KDAB/codebrowser) - Woboq CodeBrowser
- [oclint](https://github.com/oclint) - A static source code analysis tool to improve quality and reduce defects for C, C++ and Objective-C
- [CppNameLint](https://github.com/dougpuob/cppnamelint) - a naming convention linter of C/C++ source code Based on Clang libtooling


## Libraries

### LibClang

- [libclang:](https://clang.llvm.org/doxygen/group__CINDEX.html) -  C Interface to Clang.
- [Introduction to libclang](https://www.mikeash.com/pyblog/friday-qa-2014-01-24-introduction-to-libclang.html)
- [LLVM & Clang library usage samples](https://github.com/eliben/llvm-clang-samples)
- [lloccount](https://github.com/neolynx/lloccount) - C/C++ Logical Lines Of Code Counter.
- [libclangmm](https://github.com/cppit/libclangmm) - C++-wrapper for libclang (developed for [juCi++](https://github.com/cppit/jucipp))
- [Customizable Naming Convention Checker](https://github.com/mapbox/cncc/) - similar to clang-format, but for naming conventions only.
- [irony-mode](https://github.com/Sarcasm/irony-mode) - A C/C++ minor mode for Emacs powered by libclang.
- [c99-to-c89](https://github.com/libav/c99-to-c89/) - Tool to convert C99 code to MSVC-compatible C89.
- [ClangKit](https://github.com/macmade/ClangKit) - Objective-C frontend to LibClang.
- [Skipping library code in gdb with help from libClang](https://jefftrull.github.io/c++/gdb/python/libclang/llvm/2018/04/30/stepping-with-libclang.html) - using libClang’s Python bindings.

### LibTooling

- [LibTooling](https://clang.llvm.org/docs/LibTooling.html) - library to support writing standalone tools based on Clang
- [Tutorial for building tools using LibTooling and LibASTMatchers](https://clang.llvm.org/docs/LibASTMatchersTutorial.html)
- [Modern source-to-source transformation with Clang and libTooling](https://eli.thegreenplace.net/2014/05/01/modern-source-to-source-transformation-with-clang-and-libtooling)
- [AST matchers and Clang refactoring tools](https://eli.thegreenplace.net/2014/07/29/ast-matchers-and-clang-refactoring-tools)
- [Compilation databases for Clang-based tools](https://eli.thegreenplace.net/2014/05/21/compilation-databases-for-clang-based-tools)
- [LibTooling Example](https://kevinaboos.wordpress.com/2013/07/23/clang-tutorial-part-ii-libtooling-example/)

### Important Clang concepts

- [Quick overview of how Clang works internally](http://cppdepend.com/blog/?p=321)
- [Getting Started with LLVM Core Libraries](https://www.packtpub.com/application-development/getting-started-llvm-core-libraries) - PacktPub books can be a bit hit and miss, but this one is excellent. (A [PDF with updates for Clang 3.5](https://www.packtpub.com/sites/default/files/downloads/6924OS_Appendix.pdf) is available for free download).
- [Introduction to the Clang AST](https://clang.llvm.org/docs/IntroductionToTheClangAST.html) - a gentle introduction to the mysteries of the Clang AST.
- [Matching the Clang AST](https://clang.llvm.org/docs/LibASTMatchers.html) - how to use Clang’s LibASTMatchers to match interesting nodes of the AST and execute code that uses the matched nodes.
- [AST Matcher Reference](https://clang.llvm.org/docs/LibASTMatchersReference.html) - AST matchers implemented by Clang.
- [How to build LLVM from source](https://quuxplusone.github.io/blog/2018/04/16/building-llvm-from-source/) - Step-by step, using the GitHub mirror.
- [Writing LLVM Pass in 2018 — Part I](https://medium.com/@mshockwave/writing-llvm-pass-in-2018-part-i-531c700e85eb) - New Pass & Pass Manager in a Peek.

## Videos

- [Create your own Refactoring Tool in Clang](https://www.youtube.com/watch?v=8PndHo7jjHk) - Richard Thompson's presentation from C++Now 2014.
- [Refactoring C++ with Clang](https://www.youtube.com/watch?v=yuIOGfcOH0k) - Chandler Carruth's talk from C++Now 2012.
- [Automatic C++ source code generation with clang](https://www.youtube.com/watch?v=aPTyatTI42k) - Sergei Sadovnikov's ACCU 2017 talk.


## License

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.