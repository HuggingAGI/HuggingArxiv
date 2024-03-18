# [大型语言模型能够实现并行多语言学习，揭示了其在多种语言环境中同步掌握知识的能力。](https://arxiv.org/abs/2403.09073)

发布时间：2024年03月13日

`LLM应用` `` `多语种模型`

> Large Language Models are Parallel Multilingual Learners

> 本研究揭示了一项新颖发现——多语种大型语言模型具备强大的ICL能力，只需将输入翻译成多种语言形成PiM输入方式，就能有效提升模型理解力。为此，我们针对8个典型数据集、7种语言及8款顶尖多语种LLMs设计了一系列详尽实验。实验表明，引入更多语言能让PiM表现优于传统ICL；甚至与基准性能以下的翻译结果结合，也能助力提升效果。更有意思的是，我们通过观察LLMs内部激活的神经元，发现一个反常识却引人入胜的现象：PiM非但没有像预期那样大量激活神经元来整合多种语言知识，反而在加入更多语言时抑制了神经元并促进更精准的激活模式，这一现象恰好契合神经科学中“突触修剪”的原理——淘汰使用较少的神经连接，强化保留部分，进而提高智力水平。

> In this study, we reveal an in-context learning (ICL) capability of multilingual large language models (LLMs): by translating the input to several languages, we provide Parallel Input in Multiple Languages (PiM) to LLMs, which significantly enhances their comprehension abilities. To test this capability, we design extensive experiments encompassing 8 typical datasets, 7 languages and 8 state-of-the-art multilingual LLMs. Experimental results show that (1) incorporating more languages help PiM surpass the conventional ICL further; (2) even combining with the translations that are inferior to baseline performance can also help. Moreover, by examining the activated neurons in LLMs, we discover a counterintuitive but interesting phenomenon. Contrary to the common thought that PiM would activate more neurons than monolingual input to leverage knowledge learned from diverse languages, PiM actually inhibits neurons and promotes more precise neuron activation especially when more languages are added. This phenomenon aligns with the neuroscience insight about synaptic pruning, which removes less used neural connections, strengthens remainders, and then enhances brain intelligence.

[Arxiv](https://arxiv.org/abs/2403.09073)