# LLMs 如何进行标量含意的语用推理

发布时间：2024年08月13日

`LLM理论` `人工智能`

> Pragmatic inference of scalar implicature by LLMs

# 摘要

> 本研究深入探讨了BERT和GPT-2在处理标量含意（如“一些”）时的语用推理能力。实验1揭示，即便缺乏上下文，两模型均能将“一些”理解为“不是全部”，与人类语言处理相符。实验2中，引入QUD作为上下文线索，BERT表现稳定，而GPT-2则在特定QUD类型下遭遇推理难题。研究显示，BERT遵循默认模型，自然融入语用含意，而GPT-2则受限于上下文驱动模型，在复杂语境中推理能力受限。

> This study investigates how Large Language Models (LLMs), particularly BERT (Devlin et al., 2019) and GPT-2 (Radford et al., 2019), engage in pragmatic inference of scalar implicature, such as some. Two sets of experiments were conducted using cosine similarity and next sentence/token prediction as experimental methods. The results in experiment 1 showed that, both models interpret some as pragmatic implicature not all in the absence of context, aligning with human language processing. In experiment 2, in which Question Under Discussion (QUD) was presented as a contextual cue, BERT showed consistent performance regardless of types of QUDs, while GPT-2 encountered processing difficulties since a certain type of QUD required pragmatic inference for implicature. The findings revealed that, in terms of theoretical approaches, BERT inherently incorporates pragmatic implicature not all within the term some, adhering to Default model (Levinson, 2000). In contrast, GPT-2 seems to encounter processing difficulties in inferring pragmatic implicature within context, consistent with Context-driven model (Sperber and Wilson, 2002).

[Arxiv](https://arxiv.org/abs/2408.06673)