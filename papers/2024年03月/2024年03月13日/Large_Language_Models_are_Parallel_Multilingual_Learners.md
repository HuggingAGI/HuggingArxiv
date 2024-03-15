# [大型语言模型能够实现并行多语言学习，这意味着它们在处理多种语言时展现出同步学习和理解的能力。](https://arxiv.org/abs/2403.09073)

发布时间：2024年03月13日

`LLM理论`

``

`多语种模型`

> Large Language Models are Parallel Multilingual Learners

> 本研究揭示了多语种LLMs具有强大的ICL特性，只需将输入内容翻译为多种语言形成PiM输入方式，就能有效提升模型理解力。为了验证此特性，我们针对8个代表性数据集、7种语言以及8款顶尖多语种LLMs设计了一系列详尽实验。实验结果显示，增加更多语言种类能够助力PiM更好地超越传统ICL效果；甚至与低于基准性能的翻译结合使用也能带来增益。更令人惊奇的是，通过对LLMs内部激活神经元的研究，我们发现一个反常识的现象——不同于普遍认为PiM会因融合多种语言知识而激活更多神经元，实际情况是PiM反而起到了抑制神经元、促进更为精准的神经元激活的作用，尤其当引入更多语言时。这一现象恰恰印证了神经科学中的“突触修剪”原理，即淘汰不常使用的神经连接，加强留存部分，进而提升智能表现。

> In this study, we reveal an in-context learning (ICL) capability of multilingual large language models (LLMs): by translating the input to several languages, we provide Parallel Input in Multiple Languages (PiM) to LLMs, which significantly enhances their comprehension abilities. To test this capability, we design extensive experiments encompassing 8 typical datasets, 7 languages and 8 state-of-the-art multilingual LLMs. Experimental results show that (1) incorporating more languages help PiM surpass the conventional ICL further; (2) even combining with the translations that are inferior to baseline performance can also help. Moreover, by examining the activated neurons in LLMs, we discover a counterintuitive but interesting phenomenon. Contrary to the common thought that PiM would activate more neurons than monolingual input to leverage knowledge learned from diverse languages, PiM actually inhibits neurons and promotes more precise neuron activation especially when more languages are added. This phenomenon aligns with the neuroscience insight about synaptic pruning, which removes less used neural connections, strengthens remainders, and then enhances brain intelligence.