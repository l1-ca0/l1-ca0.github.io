---
title: "Summer of Computer Systems and More"
date: 2025-07-20T12:56:05Z
draft: false
tags: ["cmu", "systems", "programming"]
description: "How I spent my summer preparing for next semester's courses in computer systems and diving deeper into C++."
---


Due to the restriction that we need at least two consecutive semesters of study in order to intern in the US, I didn't apply for any summer internship. Employment at school is exempted, and I am fortunate to be an RA at CMU Tepper BLA lab this summer. It involves using graph theory to analyze financial statements. More details can be found [here](https://www.cmu.edu/tepper/news/stories/2025/april/using-graph-theory-ph.d-student-jane-jaeyeon-pyo-demystifies-financial-statements.html). I am also currently working with a PhD student at Safe AI Lab to do research in the area of Robotics.

## Course Selection 

Initially, I planned to enroll in Distributed Systems and Cloud Computing, two frequently recommended classes offered by the CS department. After spending time studying distributed systems, I found that while it covers a broad range of topics, each area felt like it needed more depth. As for cloud computing, I decided to take the Advanced Cloud Computing class later instead. I also considered Probabilistic Graphical Models from the ML department. Having already self-studied much of the material, I discovered significant overlap with the courses I'd previously taken. 

After some research, I'm planning to enroll in the Operating Systems class. It's widely regarded as the most challenging CS course at CMU, but also one of the most transformative. I'm also planning to take the Storage Systems class to complement my systems focus—it's known to be a tough but valuable course that covers everything from storage hardware and firmware to distributed file systems and cloud storage.

For my remaining courses, I'm considering several options. Embedded Systems appeals to me with its practical focus on bridging hardware and software design, while Computer Networks would deepen my understanding of the network protocols and architectures that enable global connectivity. Parallel Computer Architecture is especially compelling given my summer focus on parallel programming. I'm also drawn to Modern Control Theory for its mathematical rigor and connections to reinforcement learning. CMU offers so many good classes that I sometimes wish I could take ten courses per semester—though that's clearly unrealistic given the constraints of time and human capacity. 😅


## Summer Preparation 

Rather than simply trying to survive what promised to be an intense semester, I wanted to deepen my understanding of computer systems fundamentals and develop stronger systems programming skills.

### 1. Operating Systems 

**My Learning Resources**:
- Berkeley CS 162 
- OSTEP
- Operating Systems Principles and Practice book

**Key Insights Gained**:
- Process scheduling algorithms directly impact how responsive applications feel to users and how efficiently the system utilizes resources
- Modern computers rely fundamentally on virtual memory systems and paging mechanisms to manage the illusion of unlimited memory
- Concurrency and synchronization are fundamental challenges in modern computing
- The power of abstraction layers—how operating systems hide complexity while providing clean interfaces for applications

From other reviews online, I learned that CMU's Operating Systems class goes beyond traditional OS theory—it's fundamentally a systems design course that emphasizes writing robust, production-quality code in C. While I'm not entirely certain my preparation will be sufficient, the foundation I've built this summer has given me confidence to tackle the challenges ahead.  Richard Feynman once said, "What I cannot create, I do not understand." This quote captures my motivation for taking the OS class. 


### 2. Systems Programming with Modern C++ 

**Why This Matters**: Modern C++ offers powerful abstractions while maintaining the performance characteristics needed for systems-level programming.

**My Learning Resources**:
- Stanford CS 106L for Modern C++ 
- Cornell CS 4414 Systems Programming course (it also has a lecture on Rust which explains why Rust probably cannot replace C++)
- "C++ Concurrency in Action" for learning concurrent programming in C++
- CppCon YouTube channel for advanced C++ talks and best practices

**Practical Applications**:
- Built a HTTP server in modern C++ to practice systems programming concepts
- Implemented concurrent lockfree data structures in modern C++

### 3. Parallel Programming and Concurrency 

**The Reality**: Modern computing is inherently parallel, from multi-core processors to distributed computing clusters. GPU programming with CUDA has also become increasingly important, especially in AI where massive parallelization is crucial for training and inference. 

**My Learning Resources**:
- Stanford CS 149 
- Programming Massively Parallel Processors book

## What I Wish I Could Have Done More 

I'm also eager to explore other systems programming languages, particularly Go and Rust. Go's built-in concurrency primitives make it useful for cloud-native development, while Rust's memory safety guarantees are driving its adoption in some areas of systems development. Both languages represent interesting design philosophies that could complement my C++ knowledge, but time constraints meant I had to prioritize depth over breadth this summer. With still one month left of summer, let's see how it goes!

## Looking Forward 🌟

This summer's preparation has given me more confidence approaching the fall semester, though I know there's still much to learn. I'm excited to continue learning and diving deeper into this field. 


---
