---
title: "Visual Answer Set Programming"
date: 2022-03-26T19:58:20-07:00
---

**Visual Answer Set Programming**

I'm curious what a visual programming environment for answer set programming might look like, and if it would help make teaching predicate logic (the calculus of computer science) easier.


*Notes (reverse chronological):*

- New Name - VASP - Visual Answer Set Programming
- Cut bait. Blockly is so closely tied to the imperative and procedural programming paradigm that plugging in a declarative logic programming language generator side-by-side with an imperative language generators of Javascript, Dart, PHP, etc. doesn't really work the way I wanted it to.  I started writing a generator, and it just became too obvious.  I still feel like visualizations can be a powerful way to input declarative logic programming, guiding the programmer in ways that keep them in the declarative mindset, and keeping them from slipping back into the imperative programming mindset that even just typing in code using the ASP-CORE-2 syntax can trigger.  Not trying to change that syntax, just trying to provide a place of safety to do the thinking required for declarative programming.  So maybe provide a bespoke ASP input experience and the mind may not switch into the wrong mode of thinking so much while programming.  The goal of the visualization being to make it simple for the programmer to input programs in the declarative programming mindset, defined by Wikipedia as "what the program has to accomplish" and not "how to accomplish it" [2]. 
- Setting up the playground doesn't work without latest node and npm
- Ubuntu packages are too old, these instructions are newer: https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/setting-up-node-on-ec2-instance.html
- codelabs demo works, but has an xml custom generator, toolbox guide says to use the new json format.
- Experimenting with building a Blocklycode generator and corresponding blocks for the Answer Set Programming (ASP-Core-2) language.  "Blockly is a library from Google for building beginner-friendly block-based programming languages." [1]

*References:*

1. https://developers.google.com/blockly/guides/app-integration/attribution
2. https://en.wikipedia.org/wiki/Declarative_programming

*Related links:*
- Custom generator howto:  https://blocklycodelabs.dev/codelabs/custom-generator/index.html
- Blockly generators: https://github.com/google/blockly/tree/master/generators 
- Input language format:  https://www.mat.unical.it/aspcomp2013/files/ASP-CORE-2.03c.pdf 
- https://developers.google.com/blockly/guides/modify/web/playground
- https://developers.google.com/blockly/guides/configure/web/toolbox#json
- https://web.stanford.edu/~vinayc/logicprogramming/html/answer_set_programming.html
- https://www.cs.nmsu.edu/~tson/tutorials/asp-tutorial.pdf
- https://codedocs.org/what-is/answer-set-programming
- https://www.cs.utexas.edu/~vl/teaching/378/pwc.pdf