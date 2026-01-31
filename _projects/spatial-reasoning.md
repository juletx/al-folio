---
layout: page
title: Spatial Reasoning
description: Grounding Language Models for Compositional and Spatial Reasoning
img: assets/img/projects/spatial-reasoning.png
importance: 4
category: research
related_publications: true
---

This project evaluates grounded Neural Language models that can perform compositional and spatial reasoning.

## Motivation

Humans naturally combine vision and textual information to acquire compositional and spatial relationships among objects. When reading a text, we are able to mentally depict the spatial relationships that may appear in it.

Vision-and-Language models (VLM), trained jointly on text and image data, have been proposed to address the lack of grounding in language models. However, recent work has shown that these models struggle to ground spatial concepts properly.

## Research Goals

1. Evaluate state-of-the-art pre-trained and fine-tuned VLMs on compositional and spatial reasoning
2. Explore synthetic dataset creation methods: text-to-image generation, image captioning, and image retrieval

## Results

We managed to improve the state-of-the-art in compositional reasoning and performed zero-shot experiments on spatial reasoning.

## Resources

- 📄 Thesis: [ADDI Repository](https://addi.ehu.es/handle/10810/61827)
- 💻 Code: [GitHub](https://github.com/juletx/spatial-reasoning)
- 🤗 Models: [Hugging Face](https://huggingface.co/juletxara)

{% cite etxaniz2023grounding %}
