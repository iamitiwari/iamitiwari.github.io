---
title: "What I am reading: LLM compression"
categories: readings
---
A running list of the papers I keep coming back to while working on model
compression. I will add short notes to each as I go.

- *GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers* — the
  second-order, one-shot weight quantization method most later work builds on.
- *QuIP / QuaRot* — rotating the weight and activation space before quantization so that
  outliers stop dominating the error.
- *SparseGPT* — the pruning counterpart to GPTQ.
- *Distilling the Knowledge in a Neural Network* — the original knowledge-distillation paper,
  still the cleanest statement of the idea.
