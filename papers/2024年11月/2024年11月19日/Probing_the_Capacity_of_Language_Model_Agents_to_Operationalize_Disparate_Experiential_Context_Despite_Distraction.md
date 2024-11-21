# 探究语言模型代理在分心状态下运作各种不同经验背景的能力

发布时间：2024年11月19日

`Agent` `语言模型` `决策推理`

> Probing the Capacity of Language Model Agents to Operationalize Disparate Experiential Context Despite Distraction

# 摘要

> 大型语言模型（LLM）代理在众多领域展现出良好的发展前景。在众多提议的应用里，人们期望代理能依据输入提示中呈现的积累经验进行推理。我们推出了 OEDD（排除干扰以运用经验）语料库，这是经人类注释者验证的一系列场景集合，其中包含预先设定的代理历史，代理必须在有干扰因素的情况下依据不同的经验信息做出决策。我们运用最小的思维链提示策略对三个顶尖的 LLM（GPT-3.5 Turbo、GPT-4o 以及 Gemini 1.5 Pro）进行了评估，发现当（1）输入的上下文包含超过 1615 个令牌的历史交互信息；（2）一个对决策起关键作用的前提是从两个不同的环境前提中得出的合理结论；（3）接着出现一个琐碎但会分散注意力的误导性事实时，所有 LLM 在选择两个动作中较好的那个方面，表现都不如随机选择。我们的代码和测试语料库可在以下网址公开获取：https://github.com/sonnygeorge/OEDD 。

> Large language model (LLM) agents show promise in an increasing number of domains. In many proposed applications, it is expected that the agent reasons over accumulated experience presented in an input prompt. We propose the OEDD (Operationalize Experience Despite Distraction) corpus, a human-annotator-validated body of scenarios with pre-scripted agent histories where the agent must make a decision based on disparate experiential information in the presence of a distractor. We evaluate three state-of-the-art LLMs (GPT-3.5 Turbo, GPT-4o, and Gemini 1.5 Pro) using a minimal chain-of-thought prompting strategy and observe that when (1) the input context contains over 1,615 tokens of historical interactions, (2) a crucially decision-informing premise is the rightful conclusion over two disparate environment premises, and (3) a trivial, but distracting red herring fact follows, all LLMs perform worse than random choice at selecting the better of two actions. Our code and test corpus are publicly available at: https://github.com/sonnygeorge/OEDD .

[Arxiv](https://arxiv.org/abs/2411.12828)