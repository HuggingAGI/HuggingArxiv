# StyleRemix：借助风格元素的提炼与微调，巧妙混淆作者身份，实现可解释性。

发布时间：2024年08月28日

`LLM应用` `网络安全` `文本处理`

> StyleRemix: Interpretable Authorship Obfuscation via Distillation and Perturbation of Style Elements

# 摘要

> 作者身份混淆，即通过重写文本来隐藏作者身份，是一项既重要又具挑战的任务。现有的大型语言模型方法在这方面表现不佳，因其缺乏可解释性和可控性，且常忽略作者的独特风格特征。为此，我们推出了StyleRemix，一种既能自适应调整又能清晰解释的混淆技术，它通过微调文本的细粒度风格元素来实现目的。利用预训练的LoRA模块，StyleRemix在保持低成本的同时，针对不同风格维度进行精准重写，其效果在多个领域内均超越了现有技术和大型模型，得到了自动与人工评估的双重认可。此外，我们还公开了AuthorMix和DiSC两个资源：前者是一个包含3万篇高质量长文的多样化数据集，涵盖14位作者和4大领域；后者则是一个平行语料库，包含1,500篇文本，覆盖7个风格轴的16种不同方向。

> Authorship obfuscation, rewriting a text to intentionally obscure the identity of the author, is an important but challenging task. Current methods using large language models (LLMs) lack interpretability and controllability, often ignoring author-specific stylistic features, resulting in less robust performance overall.
  To address this, we develop StyleRemix, an adaptive and interpretable obfuscation method that perturbs specific, fine-grained style elements of the original input text. StyleRemix uses pre-trained Low Rank Adaptation (LoRA) modules to rewrite an input specifically along various stylistic axes (e.g., formality and length) while maintaining low computational cost. StyleRemix outperforms state-of-the-art baselines and much larger LLMs in a variety of domains as assessed by both automatic and human evaluation.
  Additionally, we release AuthorMix, a large set of 30K high-quality, long-form texts from a diverse set of 14 authors and 4 domains, and DiSC, a parallel corpus of 1,500 texts spanning seven style axes in 16 unique directions

[Arxiv](https://arxiv.org/abs/2408.15666)