---
layout: project
title: "Human–AI Collaboration on the Ghys Conjecture"
category: "AI for Mathematics · 2026"
order: 1
permalink: /projects/ghys-conjecture/
image: /assets/projects/ghys-torus.png
image_alt: "A fundamental parallelogram and its identification as a torus"
image_caption: "A complex torus illustration from Shanghai AI Laboratory’s report."
summary: "Helping mathematicians solve the three-dimensional Ghys conjecture through human–AI collaboration: Intern-S2 combines large-scale recursive reasoning with expert insight to tackle a problem open for more than 30 years."
---

### From competition mathematics to mathematical discovery

My work on mathematical reasoning at Shanghai AI Laboratory contributes to a broader goal: making AI a useful research partner for mathematicians. In this project, Disheng Xu and Jiesong Zhang worked with Intern-S2 and its research harness to prove the three-dimensional Ghys conjecture. A separate Peking University team led by Bin Dong and Ruochuan Liu carried out formal verification using the SHEAF framework.

Proposed by Étienne Ghys in 1995, the conjecture asks whether holomorphic Anosov dynamics on a compact complex manifold force a rigid algebraic structure. The three-dimensional case connects complex geometry and dynamical systems: seemingly chaotic motion can impose surprisingly strong constraints on the space supporting it.

### A research process shaped by human insight

The collaboration paired the model’s ability to explore many lines of reasoning with the mathematicians’ judgment about which ideas were promising. The early exploration was particularly important: an initial report of roughly **400 pages** exposed potential routes, including ideas from neighboring areas of mathematics. Experts identified useful insights, rejected dead ends, and guided subsequent exploration.

Across **seven rounds of continued reasoning**, the problem graph expanded from **15 to 389 nodes**, producing over a thousand pages of derivations. The system decomposed difficult questions, explored alternative arguments, and accumulated intermediate results; the researchers continually refined the direction and assembled the final proof.

<figure class="project-figure">
  <a href="{{ '/assets/projects/ghys-research-process.png' | relative_url }}"><img src="{{ '/assets/projects/ghys-research-process.png' | relative_url }}" alt="Seven rounds of human–AI interaction and the recursive reasoning structures within each round" loading="lazy"></a>
  <figcaption>The seven-round research process and recursive reasoning trees, reproduced from Shanghai AI Laboratory’s report. Open the image to view the details.</figcaption>
</figure>

### Verification and a reusable research workflow

According to the laboratory’s report, the Peking University team formalized all four main theorems of the resulting paper, *Codimension-one holomorphic Anosov diffeomorphisms*, with proofs checked in Lean. This verification complemented the mathematical discovery process.

The project demonstrates a workflow in which systematic exploration, expert judgment, accumulated results, and feedback reinforce one another. In my interview with Yicai, I emphasized that AI increases the amount of intellectual work researchers can carry out, while humans remain responsible for research direction and value.

### Read more

- [CoForest paper](https://zhao-ht.github.io/CoForest/CoForest.pdf)
- [CoForest project website](https://zhao-ht.github.io/CoForest/)
- [Shanghai AI Laboratory: 中国科学家首次用中国大模型攻克世界级数学难题](https://mp.weixin.qq.com/s/F1fgj4f0hHurTdEACutQvw) · October 15, 2026 (Chinese)
- [Yicai: 国产大模型攻克世界级数学难题](https://mp.weixin.qq.com/s/c61GzWbnTuaGnYONVgSMnA) · October 17, 2026 (Chinese)
- [Public formalization code: HolomorphicAnosov](https://github.com/frenzymath/HolomorphicAnosov)
