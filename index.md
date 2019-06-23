## Using the V8 JavaScript Virtual Machine as a Research Platform

In this tutorial we will give an overview over the JavaScript virtual machine V8. In particular, we will look into Javascript benchmarking with workloads and metrics, the runtime system, the parsing and compilation architecture, garbage collection, and WebAssembly. The main goal of this tutorial is to make V8 approachable for researchers, brainstorm ideas about how V8 could be more hackable, and discuss virtual machine research problems and ideas.

**Date:** June 22nd, 2019

**Time:** Afternoon session (starting at 2PM)

**Duration:** half day

### Agenda

1. [Introduction](https://hannespayer.github.io/v8-tutorial-pldi2019/v8-intro.pdf) (Hannes Payer)
  * General V8 introduction about open source, community, how to get the code and build it, documentation, design docs, etc.
  * Current research based on V8, investment, and opportunites
2. Runtime system (Toon Verwaest)
  * Object model
  * Type feedback and inline caches
  * Parsing and streaming
  * Open research problems in the runtime
3. [Compilation Pipeline](https://hannespayer.github.io/v8-tutorial-pldi2019/v8-compiler.pdf) (Michael Starzinger)
  * TurboFan overview
  * JavaScript focused optimizations
  * TurboFan usage for WebAssembly 
  * Open research problems in the compiler
4. [Garbage Collection](https://hannespayer.github.io/v8-tutorial-pldi2019/v8-gc.pdf) (Hannes Payer)
  * Architecture Overview
  * Open research problems in garbage collection
5. [MMTK in V8 research project](https://hannespayer.github.io/v8-tutorial-pldi2019/v8-mmtk.pdf) (Steve Blackburn)
6. Benchmarking in V8 & Chrome (Ulan Degenbaev)
  * Real-world benchmarking
  * Performance traces
  * Metrics and performance evaluation
  * Developer tooling and inspector protocol
  

### Organizers & Presenters

[Steve Blackburn, Professor, Research School of Computer Science at the Australian National University](http://users.cecs.anu.edu.au/~steveb/)<br>
Steve Blackburn is a professor in the Research School of Computer Science at the Australian National University.  His research interests include programming language implementation, architecture, and performance analysis.  Steve leads the MMTk memory management project, and the DaCapo benchmark project and co-leads the Mu micro virtual machine project.  He was heavily involved in the development of Jikes RVM.  Steve is a Fellow of the Association for Computing Machinery.

[Ulan Degenbaev, Software Engineer, Google Munich](https://ai.google/research/people/UlanDegenbaev)<br>
Ulan is a Software Engineer working on garbage collection and benchmarking of V8. Before joining Google he received a PhD in Computer Science in 2012 from Saarland University working on verification and formal specification.

[Hannes Payer, Software Engineer, Google Munich](https://ai.google/research/people/HannesPayer)<br>
Hannes Payer is a software engineer at Google where he leads the V8 Desktop team. Prior to V8, Hannes worked on various virtual machine projects like Google's Dart virtual machine and the Maxine Java research virtual machine from Sun Labs. Hannes received a PhD from the University of Salzburg in 2012 where he was the principal investigator of the Scal project.


[Michael Starzinger, Software Engineer, Google Munich](https://ai.google/research/people/MichaelStarzinger)<br>
Michael Starzinger is a software engineer at Google working on the V8 team in Munich. He is currently working on V8’s WebAssembly implementation and generally interested in compiler and garbage collector development. Before joining Google in 2011, he worked on Cacao, an open-source Java virtual machine developed by the compilers and languages group at the Vienna University of Technology. He has a masters degree in Computer Science from the Vienna University of Technology.

Toon Verwaest, Software Engineer, Google Munich<br>
Toon is a software engineer at Google working on V8 since over 6 years, where he’s the tech lead of the runtime team. He is currently focusing on improving load-time in the browser as measured by real-world benchmarks. Before joining Google he received a PhD from the University of Bern.
