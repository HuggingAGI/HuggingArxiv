# LLM 是否在社会维度上公平？让我们带着批判的眼光来探讨。

发布时间：2024年10月16日

`LLM理论` `人工智能` `社会科学`

> With a Grain of SALT: Are LLMs Fair Across Social Dimensions?

# 摘要

> 本文深入探讨了开源大型语言模型（LLM）在性别、宗教和种族方面的偏见。我们设计了一套包含七个偏见触发器的检测方法，涵盖辩论、职业建议、故事生成等多个领域。通过 GPT-4o，我们为不同群体生成了多样化的测试提示，并在 Llama 和 Gemma 模型上进行了评估。为确保公正，我们使用 GPT-4o-mini 对生成的文本进行匿名化，并借助 GPT-4o-as-a-Judge 进行成对比较，以量化偏见程度。我们的研究跨越英语、德语和阿拉伯语，揭示了语言对偏见显现的影响。研究发现，LLM 在各模型中对某些群体的偏见表现一致，但语言切换时，文化差异和上下文变化导致偏见表现出现波动。

> This paper presents an analysis of biases in open-source Large Language Models (LLMs) across various genders, religions, and races. We introduce a methodology for generating a bias detection dataset using seven bias triggers: General Debate, Positioned Debate, Career Advice, Story Generation, Problem-Solving, Cover-Letter Writing, and CV Generation. We use GPT-4o to generate a diverse set of prompts for each trigger across various genders, religious and racial groups. We evaluate models from Llama and Gemma family on the generated dataset. We anonymise the LLM-generated text associated with each group using GPT-4o-mini and do a pairwise comparison using GPT-4o-as-a-Judge. To quantify bias in the LLM-generated text we use the number of wins and losses in the pairwise comparison. Our analysis spans three languages, English, German, and Arabic to explore how language influences bias manifestation. Our findings reveal that LLMs exhibit strong polarization toward certain groups across each category, with a notable consistency observed across models. However, when switching languages, variations and anomalies emerge, often attributable to cultural cues and contextual differences.

[Arxiv](https://arxiv.org/abs/2410.12499)