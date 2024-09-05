# 多即是优：探讨大型语言模型中的加法倾向

发布时间：2024年09月04日

`LLM理论` `人工智能` `可持续发展`

> More is More: Addition Bias in Large Language Models

# 摘要

> 本文深入研究了大型语言模型（LLMs）中的加法偏差现象，这一现象与人类认知中的加法偏好相似。我们通过一系列精心设计的实验，对GPT-3.5 Turbo、Claude 3.5 Sonnet、Mistral、Math$Σ$tral和Llama 3.1等模型进行了测试，旨在揭示它们在加法与减法修改上的倾向。实验结果显示，所有模型均显著倾向于加法变化。例如，在回文创作任务中，Llama 3.1高达97.85%的情况下选择添加字母。同样，在乐高塔平衡任务中，GPT-3.5 Turbo有76.38%的选择是添加砖块。在文本摘要任务中，Mistral 7B在改进写作时，更长的摘要出现频率为59.40%至75.10%。这些发现表明，LLMs如同人类一样，存在明显的加法偏差，这在大规模应用中可能带来资源过度消耗和环境负担，增加经济成本。因此，在LLMs的开发与应用过程中，必须重视并平衡这一偏差，以实现更高效、更可持续的问题解决策略。

> In this paper, we investigate the presence of additive bias in Large Language Models (LLMs), drawing a parallel to the cognitive bias observed in humans where individuals tend to favor additive over subtractive changes. Using a series of controlled experiments, we tested various LLMs, including GPT-3.5 Turbo, Claude 3.5 Sonnet, Mistral, Math$Σ$tral, and Llama 3.1, on tasks designed to measure their propensity for additive versus subtractive modifications. Our findings demonstrate a significant preference for additive changes across all tested models. For example, in a palindrome creation task, Llama 3.1 favored adding letters 97.85% of the time over removing them. Similarly, in a Lego tower balancing task, GPT-3.5 Turbo chose to add a brick 76.38% of the time rather than remove one. In a text summarization task, Mistral 7B produced longer summaries in 59.40% to 75.10% of cases when asked to improve its own or others' writing. These results indicate that, similar to humans, LLMs exhibit a marked additive bias, which might have implications when LLMs are used on a large scale. Addittive bias might increase resource use and environmental impact, leading to higher economic costs due to overconsumption and waste. This bias should be considered in the development and application of LLMs to ensure balanced and efficient problem-solving approaches.

[Arxiv](https://arxiv.org/abs/2409.02569)