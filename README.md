# Awesome Program Synthesis
This repository hosts a curated collection of research papers focused on program synthesis and automatic programming. The list is carefully maintained by Mikah Đặng.

Contributions are highly encouraged! If you have suggestions to improve the list, make it more comprehensive, or spot any errors, feel free to submit a pull request or email me.

# Nature‐Inspired & Evolutionary Methods
Grammatical Evolution: Evolving Programs for an Arbitrary Language
This foundational work (by Ryan, Collins, and O’Neill, 1998) introduced grammatical evolution—a technique that uses a user‐defined grammar (typically in Backus–Naur form) to evolve syntactically valid programs.
Implementations of grammatical evolution are available in open-source projects such as PonyGE, PyNeurGen, and gramEvol for R.
[https://www.researchgate.net/publication/216301188_Grammatical_Evolution_Evolutionary_Automatic_Programming_in_an_Arbitrary_Language]

Automated Program Synthesis via Genetic Programming
Various works in genetic programming have tackled program synthesis by evolving code fragments or complete programs. Many libraries (e.g., DEAP) and frameworks offer open implementations for experimenting with these ideas.
[https://www.researchgate.net/publication/308894433_Automatic_Synthesis_of_Code_Using_Genetic_Programming]

# LLM-Based Approaches

Program Synthesis with Large Language Models (Austin et al., 2021)
This paper investigates how transformer-based language models (ranging from 244M to 137B parameters) can synthesize Python programs from natural language descriptions. It introduces new benchmarks (MBPP and MathQA-Python) and demonstrates that synthesis performance scales log-linearly with model size.
Code and benchmark details are available on Papers With Code.
[https://arxiv.org/abs/2108.07732]

CodeGen: An Open Large Language Model for Code with Multi-Turn Program Synthesis (Nijkamp et al., 2022)
Introducing the CODEGEN family of models, this work demonstrates how multi-turn synthesis (breaking a programming task into sequential sub-tasks) can improve code generation. The authors open-sourced both the model and the training library (JAXFORMER).
Repository and paper details can be found on GitHub (salesforce/CodeGen) and arXiv.
[https://arxiv.org/abs/2203.13474]

CodeGen2: Lessons for Training LLMs on Programming and Natural Languages (Nijkamp et al., 2023)
[https://arxiv.org/abs/2305.02309]
As a follow-up, CodeGen2 distills insights and techniques for training more efficient LLMs tailored for programming tasks, sharing lessons learned and improvements over previous versions.
This paper is also available with open-source code on GitHub.
