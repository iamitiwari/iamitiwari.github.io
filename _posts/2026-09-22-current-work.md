---
title: "Current work: how small can a language model get?"
categories: research
---
My current project asks a simple question: how far can a pretrained language model be
compressed before it stops being useful, and which combination of techniques gets the
most capability per byte?

The tools on the table are post-training quantization, structured and unstructured
pruning, and recovering lost accuracy with a short distillation run from the original
model. The interesting part is not any single method but how they interact: a model that
looks fine on perplexity can fall apart on reasoning benchmarks, so evaluation matters as
much as the compression itself.

I will post write-ups here as results firm up.
