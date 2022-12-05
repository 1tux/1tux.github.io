---
layout: post
title: 'Computation: Beyond artificial machines'
published: true
---
The idea of computation is probably the single most important idea that emerged in the past century. Of course it has been brought us all the computer technology we have today and so on. But there’s actually a lot more to computation than that. It’s a very deep, very powerful, very fundamental idea whose effects we’ve only just begin to see.

Computation is generally described as the process of applying simple, local rules repeatedly to an environment. For example, weather, proteins in a cell, epidemics, fire, anthills, and so on. This definition seems too general and abstract to be useful. Surprisingly, Turing Machines fully capture this idea.

In 1936, Alan Turing proposed Turing Machines, hypothetical machines that could perform any computation. The core principle is that any computational process (fire for instance) can be imitated by providing an input (fuel, oxygen, heat), internal states (the status of each molecule and the temperature), and models for transforming between states (how the status of each molecule affects the other and the temperature). Each algorithm, computational process or machine has a matching Turing Machine.

There is a very special TM, one that could take as an input a description of any TM with an input for it and emulate its execution over the input. This is remarkable as we can now build a single universal machine that does ALL the computation. Compilers and interpreters exist today, so it is not surprising that this machine exists; however, it lets us use Turing Machines as code that will be executed.

Together, these two profound ideas form the basis for a general purpose computing machine – the computer. When computer-scientists refer to the brain as a computer, they are not referring to the silicon, RAM, or some set of instructions that govern each and every action of it, but rather to the fact that it is also a general purpose computing machine, one that can be emulated with a Turing machine and obeys computational laws. Laws such as the inability to solve the halting problem, laws regarding representation, error correcting code, and algorithmic lower bounds.

The brain is an instrument of computation, just like a personal computer. It is similar to how music instruments can play the same notes, even though they produce sound differently. Since we are interested in thinking (the music itself) that is performed by the brain (musical instrument), examining the brain's (guitar's) properties in ever greater detail does not make any sense to us. We should rather focus on music theory. Asking 'what kind of musical piece have the properties of the mind?' namely, what type of software can produce thinking.

> "The only constructive theory connecting neuroscience and psychology will arise from the study of software.” - Alan J. Perlis

Computer science could contribute to neuroscience by making clear that computation governs the mind, the software running over the brain's biological hardware. A person's brain, on the other hand, is a living proof that machines and computers are capable of identifying patterns, understanding language, making jokes, and so on... The brain also provides inspiration for the design of such machine by leveraging a neural network architecture that learns from experience.

A multidisciplinary approach to AI and neuroscience focuses on the principles of intelligence rather than the implementation aspects (biological / engineering). Biological neural networks are loosely related to artificial ones, which is often one of the criticisms of this approach. We will examine this more in our next post...
