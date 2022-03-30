---
title: "Block ASP"
date: 2022-03-26T19:58:20-07:00
---

Starting a project to attempt to build a Blockly code generator and corresponding blocks for the Answer Set Programming (ASP-Core-2) language.  "Blockly is a library from Google for building beginner-friendly block-based programming languages." [1]

Notes: 
- Setting up the playground doesn't work without latest node and npm
- Ubuntu packages are too old, these instructions are newer: https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/setting-up-node-on-ec2-instance.html
- codelabs demo works, but has an xml custom generator, toolbox guide says to use the new json format.

Links:

[1] https://developers.google.com/blockly/guides/app-integration/attribution
- Custom generator howto:  https://blocklycodelabs.dev/codelabs/custom-generator/index.html
- Blockly generators: https://github.com/google/blockly/tree/master/generators 
- Input language format:  https://www.mat.unical.it/aspcomp2013/files/ASP-CORE-2.03c.pdf 
- https://developers.google.com/blockly/guides/modify/web/playground
- https://developers.google.com/blockly/guides/configure/web/toolbox#json
- https://web.stanford.edu/~vinayc/logicprogramming/html/answer_set_programming.html
- https://www.cs.nmsu.edu/~tson/tutorials/asp-tutorial.pdf
- https://codedocs.org/what-is/answer-set-programming
