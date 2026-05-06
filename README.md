# Scientific / Medical Text Simplification

This repository contains an ongoing NLP project focused on sentence-level simplification of technical and medical text.

## Project Overview
The goal of this project is to develop and evaluate AI-based methods for simplifying complex scientific or medical sentences while preserving their meaning.

The work is being developed in the context of shared-task style research, with inspiration from the CLEF SimpleText task on text simplification.

## Data Set
https://github.com/JanB100/cochrane-auto

## Current Focus
The current system explores:
- prompt-based simplification
- planning-based LLM approaches
- operation-oriented simplification strategies such as rephrasing, splitting, and deletion
- dictionary-guided prompting for medical terminology support

## Dictionary-Guided Prompting
One component of the project uses a lightweight glossary-based method:
- identify medical terms in the input sentence
- retrieve concise definitions from a medical glossary or term resource
- inject these definitions into the prompt
- guide the model toward clearer term substitution during simplification

This is a lightweight retrieval-assisted prompting approach rather than a full RAG pipeline.

## Status
This project is still under development.
The repository may include ongoing experiments, partial implementations, and iterative improvements.

## Research Context
This work is related to sentence simplification research and is being developed with reference to the CLEF SimpleText shared-task setting. At the current stage, the repository documents ongoing development and experimentation rather than a finalized competition submission.

## Tools and Methods
- Python
- scikit-learn
- Hugging Face Transformers
- LLM prompting
- glossary-guided prompting
- evaluation with simplification-oriented metrics

## Planned Next Steps
- improve operation selection
- refine prompting strategies
- strengthen evaluation pipeline
- compare more simplification variants
- prepare cleaner experimental reporting
