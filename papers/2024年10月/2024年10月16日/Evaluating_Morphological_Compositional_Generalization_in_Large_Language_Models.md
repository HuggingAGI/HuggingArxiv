# 探究大型语言模型中的形态组合泛化能力

发布时间：2024年10月16日

`LLM理论` `人工智能`

> Evaluating Morphological Compositional Generalization in Large Language Models

# 摘要

> 大型语言模型 (LLMs) 在自然语言生成和理解任务中取得了显著进展，但其语言泛化能力仍存疑。人类在语言使用中展现出组合泛化和创造力，而 LLMs 在形态学方面的这些能力尚未充分探索。我们通过组合性视角，系统研究了 LLMs 的形态泛化能力，定义词素为组合性原语，并设计新任务评估形态生产力和系统性。我们评估了 GPT-4 和 Gemini 等最先进的多语言模型，发现 LLMs 在处理新词根时，尤其难以进行形态组合泛化，且随着形态复杂性增加，性能急剧下降。尽管模型在识别单个形态组合方面表现优于随机猜测，但缺乏系统性，导致与人类相比存在显著的准确性差距。

> Large language models (LLMs) have demonstrated significant progress in various natural language generation and understanding tasks. However, their linguistic generalization capabilities remain questionable, raising doubts about whether these models learn language similarly to humans. While humans exhibit compositional generalization and linguistic creativity in language use, the extent to which LLMs replicate these abilities, particularly in morphology, is under-explored. In this work, we systematically investigate the morphological generalization abilities of LLMs through the lens of compositionality. We define morphemes as compositional primitives and design a novel suite of generative and discriminative tasks to assess morphological productivity and systematicity. Focusing on agglutinative languages such as Turkish and Finnish, we evaluate several state-of-the-art instruction-finetuned multilingual models, including GPT-4 and Gemini. Our analysis shows that LLMs struggle with morphological compositional generalization particularly when applied to novel word roots, with performance declining sharply as morphological complexity increases. While models can identify individual morphological combinations better than chance, their performance lacks systematicity, leading to significant accuracy gaps compared to humans.

[Arxiv](https://arxiv.org/abs/2410.12656)