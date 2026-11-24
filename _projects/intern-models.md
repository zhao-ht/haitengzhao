---
layout: project
title: "Building the Intern Family of Foundation Models"
category: "Foundation Models · Intern-S2"
order: 2
permalink: /projects/intern-models/
image: /assets/projects/intern-s2.png
image_compact: true
image_alt: "Official Intern-S2 model banner"
image_caption: "Official artwork from the Intern-S2-397B model repository."
summary: "Contributing to the Intern family of large models, with a particular focus on Intern-S2-397B: a scientific multimodal foundation model with leading mathematical reasoning among open-source models."
---

### Scientific intelligence and advanced reasoning

At Shanghai AI Laboratory, I contribute to the development of the Intern family of foundation models. My research interests in advanced reasoning, reinforcement learning, and AI for science come together in this effort, particularly in the latest **Intern-S2-397B**.

Intern-S2 is designed for scientific intelligence and long-horizon agents. Its development scales pre-training, reinforcement-learning task coverage, and interactive agent environments to improve general reasoning, scientific problem solving, and extended tool-based workflows.

### Mathematical reasoning at the frontier

Mathematics is a central test of a model’s ability to reason precisely over long sequences of steps. Shanghai AI Laboratory’s October 2026 report describes Intern-S2 as leading existing open-source models overall on benchmarks such as **IMO-Proof** and **AdvancedMathBench**, with some results exceeding leading closed-source models. These results reflect the evaluations reported at release.

The same focus on rigorous, long-horizon reasoning underpins the [human–AI collaboration on the three-dimensional Ghys conjecture]({{ '/projects/ghys-conjecture/' | relative_url }}), where the model worked within a research harness guided by mathematicians.

### Beyond text-only reasoning

The official model card highlights three complementary directions:

- **Learning from scientific literature:** visual pre-training directly on raw document pages preserves relationships between text, symbols, and figures.
- **Scientific reasoning and generation:** joint reinforcement learning across more than 20 scientific domains supports both general reasoning and specialized tasks, including biomolecular interaction design and material structure generation.
- **Long-horizon agents:** training with agent frameworks and sandboxed environments strengthens extended workflows in general and scientific settings.

Together, these capabilities support the goal of moving from answering isolated questions toward assisting sustained scientific research.

### Models and resources

- [Intern-S2-397B: model weights, evaluations, and deployment instructions](https://huggingface.co/internlm/Intern-S2-397B)
- [InternLM on Hugging Face](https://huggingface.co/internlm/)
- [Intern-S2 model collection](https://huggingface.co/collections/internlm/intern-s2)
- [Try the Intern assistant](https://chat.intern-ai.org.cn/)
- [Shanghai AI Laboratory’s report on research-level mathematical reasoning](https://mp.weixin.qq.com/s/F1fgj4f0hHurTdEACutQvw) (Chinese)
