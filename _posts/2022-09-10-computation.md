---
layout: post
title: 'Computation: Beyond artificial machines'
published: true
---
The idea of computation is probably the single most important idea that emerged in the past century. Of course it has been brought us all the computer technology we have today and so on. But there’s actually a lot more to computation than that. It’s a very deep, very powerful, very fundamental idea whose effects we’ve only just begin to see.

The concepts presented in this post are beautifully described in Hofstader's books:
<center> <img src="https://m.media-amazon.com/images/I/41K3w2JFP1L._AC_SY780_.jpg" height=150px alt="Godel Escher Bach"> <img src="https://m.media-amazon.com/images/I/515BFnlnNML._AC_SY780_.jpg" alt="I am a strange loop" height="150px">

Computation is generally described as the process of applying simple, local rules repeatedly to an environment. For example, weather, proteins in a cell, epidemics, fire, anthills, and so on. This definition seems too general and abstract to be useful. Surprisingly, Turing Machines fully capture this idea.

In 1936, Alan Turing proposed Turing Machines, hypothetical machines that could perform any computation. The core principle is that any computational process (fire for instance) can be imitated by providing an input (fuel, oxygen, heat), internal states (the status of each molecule and the temperature), and models for transforming between states (how the status of each molecule affects the other and the temperature). Each algorithm, computational process or machine has a matching Turing Machine.

There is a very special TM, one that could take as an input a description of any TM with an input for it and emulate its execution over the input. This is remarkable as we can now build a single universal machine that does ALL the computation. Compilers and interpreters exist today, so it is not surprising that this machine exists; however, it lets us use Turing Machines as code that will be executed.

Together, these two profound ideas form the basis for a general purpose computing machine – the computer. When computer-scientists refer to the brain as a computer, they are not referring to the silicon, RAM, or some set of instructions that govern each and every action of it, but rather to the fact that it is also a general purpose computing machine, one that can be emulated with a Turing machine and obeys computational laws. Laws such as the inability to solve the halting problem, laws regarding representation, error correcting code, and algorithmic lower bounds.

The brain is an instrument of computation, just like a personal computer. It is similar to how music instruments can play the same notes, even though they produce sound differently. Since we are interested in thinking (the music itself) that is performed by the brain (musical instrument), examining the brain's (guitar's) properties in ever greater detail does not make any sense to us. We should rather focus on music theory. Asking 'what kind of musical piece have the properties of the mind?' namely, what type of software can produce thinking.

> "The only constructive theory connecting neuroscience and psychology will arise from the study of software.” - Alan J. Perlis

Previously, we asked, "Can we understand biological computations without biology?"
I hope this post makes it clear that it could be done. It is important to emphasize that the brain is a general purpose machine, which means it can execute algorithms without biological rewiring. Our understanding of this is simply based on the differences in timescales between thought and biological processes. This general purpose machine is implemented using biology and other underlying layers, but the computation it performs can be described separately once it is implemented.

Computer science could contribute to neuroscience by making clear that computation governs the mind, the software running over the brain's biological hardware. In this sense, it resolves the philosophical dualism debate of matter and souls. The notion of software detached from implementation bridges the gap between biology and psychology, and can offer explaination to terms like: self, conciousness, and free will. A person's brain, on the other hand, is a living proof that machines and computers are capable of identifying patterns, understanding language, making jokes, and so on... The brain also provides inspiration for the design of such machine by leveraging a neural network architecture that learns from experience.

A multidisciplinary approach to AI and neuroscience focuses on the principles of intelligence rather than the implementation aspects (biological / engineering). Biological neural networks are loosely related to artificial ones, which is often one of the criticisms of this approach. We will examine this more in our next post...