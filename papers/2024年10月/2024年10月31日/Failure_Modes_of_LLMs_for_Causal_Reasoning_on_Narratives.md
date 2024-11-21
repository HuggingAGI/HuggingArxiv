# LLMs 于叙事因果推理方面的失败模式

发布时间：2024年10月31日

`LLM应用` `语言模型` `因果推理`

> Failure Modes of LLMs for Causal Reasoning on Narratives

# 摘要

> 在这项工作里，我们借由从叙述中推断因果关系这一典型问题，对大型语言模型（LLMs）的因果推理能力展开研究。我们发现，即便是最前沿的语言模型，在叙述呈现和参数知识方面，都依赖于不靠谱的捷径。举例来说，LLMs 往往依据事件的拓扑排序（即，较早事件引发较晚事件）来判定因果关系，一旦事件未按确切的因果顺序叙述，性能就会下降。同样，我们证实 LLMs 在长期因果推理上存在难题，当叙述冗长且包含众多事件时，常常会失败。另外，我们表明 LLMs 似乎过度依赖其参数知识，而忽视了对所提供叙述的推理。一旦叙述与参数知识相冲突，就会削弱其能力。我们通过精心设计的综合实验以及对真实世界叙述的评估，对这些失败模式进行了广泛验证。最后，我们发现，明确生成因果图通常能提升性能，而简单的思维链却效果不佳。总之，我们的成果提炼出了当前顶尖模型的精准失败模式，能够为未来强化 LLMs 中的因果推理技术铺平道路。

> In this work, we investigate the causal reasoning abilities of large language models (LLMs) through the representative problem of inferring causal relationships from narratives. We find that even state-of-the-art language models rely on unreliable shortcuts, both in terms of the narrative presentation and their parametric knowledge. For example, LLMs tend to determine causal relationships based on the topological ordering of events (i.e., earlier events cause later ones), resulting in lower performance whenever events are not narrated in their exact causal order. Similarly, we demonstrate that LLMs struggle with long-term causal reasoning and often fail when the narratives are long and contain many events. Additionally, we show LLMs appear to rely heavily on their parametric knowledge at the expense of reasoning over the provided narrative. This degrades their abilities whenever the narrative opposes parametric knowledge. We extensively validate these failure modes through carefully controlled synthetic experiments, as well as evaluations on real-world narratives. Finally, we observe that explicitly generating a causal graph generally improves performance while naive chain-of-thought is ineffective. Collectively, our results distill precise failure modes of current state-of-the-art models and can pave the way for future techniques to enhance causal reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2410.23884)