# Simple agent AI - Materials Science and Engineering
A demo code of agent AI for calculating Gibbs energy of Fe alloys and phase decomposition by phase-field method.

## Installation

The agent part is written by JupyterNotebook with libraly of LangGraph, and we used local LLM enviroment [Ollama](https://ollama.com/) with Qwen 3.8 as LLM model. So please install Ollama with Qwen 3.8 first.

## Run

Running JupyterNotebook code will calculate and display the Gibbs energy and phase decomposition.

By default, the grain interior is set as FCC single-phase, but you can run the calculation considering other equilibrium phases by reversing the comment-outs in lines 13 and 14.

## Modification

This is a simple framework to construct the agent AI system which calculate the elemental programs in materials science and engineering.

You can mofify the sample codes by relaceing the tools part to your original code.

## Reference

If you use this code in your work, please cite the reference bellow.

[T. Koyama, Y. Matsuoka and A. Ishii, Simple implementation examples of agent AI in materials science and engineering: STAM-Methods, (2025).](https://doi.org/10.1080/27660400.2022.2112915) 

