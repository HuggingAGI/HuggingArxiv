# 温度是否决定了大型语言模型的创造力？

发布时间：2024年05月01日

`LLM应用` `创意写作` `人工智能`

> Is Temperature the Creativity Parameter of Large Language Models?

# 摘要

> 大型语言模型（LLM）在众多创意任务中大展身手，其成果或优美、或奇特、或模仿、甚至不乏抄袭之作。LLM中的温度参数控制着随机性，催生多样化的输出，因而被广泛认为是激发创造力的关键。本研究通过固定叙事生成任务的上下文、模型和提示，对这一观点进行了实证检验。我们依据叙事生成中创新性的四个要素——新颖度、典型性、紧密度和连贯性——对不同温度设置下的LLM输出进行了细致分析。研究发现，温度与新颖度的关联并不显著，与不连贯性有中等程度的相关性，但与紧密度和典型性并无直接联系。然而，温度对创造力的影响远比所谓的“创造力调节器”更为复杂和微弱。总体而言，LLM在温度升高时产生的输出新颖度略有提升。文末，我们探讨了如何更精细地控制LLM的创造力，而非单纯依赖于调整温度参数这一随机性因素。

> Large language models (LLMs) are applied to all sorts of creative tasks, and their outputs vary from beautiful, to peculiar, to pastiche, into plain plagiarism. The temperature parameter of an LLM regulates the amount of randomness, leading to more diverse outputs; therefore, it is often claimed to be the creativity parameter. Here, we investigate this claim using a narrative generation task with a predetermined fixed context, model and prompt. Specifically, we present an empirical analysis of the LLM output for different temperature values using four necessary conditions for creativity in narrative generation: novelty, typicality, cohesion, and coherence. We find that temperature is weakly correlated with novelty, and unsurprisingly, moderately correlated with incoherence, but there is no relationship with either cohesion or typicality. However, the influence of temperature on creativity is far more nuanced and weak than suggested by the "creativity parameter" claim; overall results suggest that the LLM generates slightly more novel outputs as temperatures get higher. Finally, we discuss ideas to allow more controlled LLM creativity, rather than relying on chance via changing the temperature parameter.

![温度是否决定了大型语言模型的创造力？](../../../paper_images/2405.00492/comp_eval_perplexity_write.png)

![温度是否决定了大型语言模型的创造力？](../../../paper_images/2405.00492/comp_eval_cossim_write.png)

![温度是否决定了大型语言模型的创造力？](../../../paper_images/2405.00492/comp_eval_normeditdist_write.png)

![温度是否决定了大型语言模型的创造力？](../../../paper_images/2405.00492/pca_embeddings_per_temperature.png)

[Arxiv](https://arxiv.org/abs/2405.00492)