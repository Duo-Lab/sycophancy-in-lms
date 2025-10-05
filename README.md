#

<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=24&pause=1000&color=2D9CCD&width=435&lines=Sycophancy+in+Language+Models)](https://git.io/typing-svg)

</div>

This repository explores sycophancy in language models (LMs), the tendency
of models to agree with user opinions without regard to truth or reasoning.  
We investigate whether fine-tuning on general benchmarks
(e.g., MMLU, GSM8K, HellaSwag, TruthfulQA) affects a model’s susceptibility to
sycophantic responses.

---

## Project Overview

General benchmarks like MMLU, GSM8K, HellaSwag, and TruthfulQA
are widely used to improve and evaluate language models, but their influence
on model behavior is poorly understood. While sycophancy has mostly been linked
to RLHF, we propose a broader hypothesis:

> **Optimizing models for high benchmark performance may unintentionally encourage
> sycophantic behavior by rewarding answer conformity over truth-seeking.**

This project investigates whether benchmark fine-tuning acts as a hidden
driver of sycophancy. We compare the model before and after fine-tuning
to observe changes in:

- Independence of reasoning  
- Truth alignment  
- Agreement bias toward user opinions

By evaluating both versions using SycophancyEval, we aim to determine whether
improving benchmark scores correlates with an increase in sycophantic responses.

---

```md
🚧 This repository is a work in progress. Updates, experiments, and results are
being added continuously.
```
