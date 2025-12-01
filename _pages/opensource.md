---
title: Open code and data
layout: page
keywords: open-source, models, datasets, NLP
# permalink: '/
nav_order: 9
# parent: Introduction
---

# Open-source code and datasets

The group has put a lot of effort into achieving impact through open
source software releases. As well as the efforts of faculty and
students, we have been greatly aided in doing this by the people who
have worked as research software engineers for the group: Chris Cox,
Anna Rafferty, John Bauer, and Jason Bolton.

## Stanford CoreNLP

Stanford NLP was an early proponent of releasing NLP software with
open source licenses, starting with the Stanford Parser in 2002,
followed by other tools for part-of-speech tagging, and named entity
recognition. These tools and other tools written in Java for coreference resolution and
relation extraction were tied together in [Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/), which was
released open source from 2010 on. Stanford CoreNLP was one of the
most-used NLP tools in the world, used by academics, companies,
government agencies, and non-profits. The commercially licensed
version is [listed as a notable invention by Stanford's Office of
Technology
Licensing](https://facts.stanford.edu/research/technology-inventions).

## Stanza

In the late 2010s, we produced [Stanza](https://stanfordnlp.github.io/stanza/), an all-neural Python-based
package, which covered many of the same NLP tasks but worked on a much
broader range of languages, exploiting the data gathering strategy of
Universal Dependencies, a project we participated in

## DSPy

The 2020s saw the release of [DSPy](https://dspy.ai/), a declarative framework for
building modular language model programs, by regarding language model
programming as an exercise in structured programming. DSPy has rapidly
become our most-adopted piece of software.

## Alpaca

The Stanford Alpaca code and related releases for evaluation and RLHF
have been broadly copied and adopted.

## Other software

Many of our other research projects are also accompanied by
open-source software releases. Some of the more notable ones are:
the DSIR large-scale data selection framework for LLM pre-training, 
the GloVe word vectors code,
the PyReFT library for representation finetuning,
the package for TreeLSTM neural networks,
the PyVene library for interventions in neural networks,
the string2string algorithms library, 
MAC networks for machine reasoning, 
the Phrasal statistical machine translation library,
an ArXiv paper assistant, 
and
LLaVAR for visual instruction  tuning.

## Open data and benchmarks

We have also released many influential datasets and evaluations
including:

- The Stanford Question Answering Dataset (SQuAD)
- The Stanford Sentiment Treebank (SST)
- The Stanford Natural Language Inference dataset (SNLI)
- The Holistic Evaluation of Language Models (HELM) benchmark
- WILDS: A benchmark of in-the-wild distribution shifts
- Alpaca Eval evaluation of instruction-following LLMs

