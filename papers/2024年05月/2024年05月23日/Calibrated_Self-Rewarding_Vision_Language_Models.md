# 精准自赏的视语模型

发布时间：2024年05月23日

`LLM应用

理由：这篇论文主要讨论了大型视觉-语言模型（LVLMs）在处理视觉和语言数据时的幻觉问题，并提出了一种名为校准自我奖励（CSR）的方法来解决这一问题。这种方法通过迭代生成与评估响应，并微调偏好数据，以实现模型的自我提升。论文的重点在于应用层面的改进和优化，即如何通过技术手段提高模型的性能和减少幻觉现象，而不是在理论层面探讨LLM的基本原理或Agent的行为机制。因此，这篇论文更适合归类于LLM应用。` `视觉-语言模型` `人工智能`

> Calibrated Self-Rewarding Vision Language Models

# 摘要

> 通过指令调谐，大型视觉-语言模型（LVLMs）成功融合了预训练的大型语言模型（LLMs）与视觉模型，取得了显著进展。然而，这些模型常出现幻觉现象，生成的文本看似合理却与图像内容相悖，揭示了图像与文本间的不匹配。这种不匹配源于模型对文本信息的过度依赖，即便视觉和语言数据质量均高。现有方法通过额外模型或人工注释优化模态对齐，但往往未能准确捕捉目标LVLM的偏好。为此，我们提出了校准自我奖励（CSR）方法，通过迭代生成与评估响应，以及微调偏好数据，实现模型的自我提升。在奖励建模中，我们引入视觉约束，强调视觉输入的重要性。实证显示，CSR在十个测试中显著提升了性能并减少了幻觉，超越现有方法7.62%。理论分析进一步证实了视觉约束在自我奖励机制中的有效性。CSR不仅兼容多种视觉-语言模型，还能通过迭代微调持续提升性能。相关数据和代码已公开于https://github.com/YiyangZhou/CSR。

> Large Vision-Language Models (LVLMs) have made substantial progress by integrating pre-trained large language models (LLMs) and vision models through instruction tuning. Despite these advancements, LVLMs often exhibit the hallucination phenomenon, where generated text responses appear linguistically plausible but contradict the input image, indicating a misalignment between image and text pairs. This misalignment arises because the model tends to prioritize textual information over visual input, even when both the language model and visual representations are of high quality. Existing methods leverage additional models or human annotations to curate preference data and enhance modality alignment through preference optimization. These approaches may not effectively reflect the target LVLM's preferences, making the curated preferences easily distinguishable. Our work addresses these challenges by proposing the Calibrated Self-Rewarding (CSR) approach, which enables the model to self-improve by iteratively generating candidate responses, evaluating the reward for each response, and curating preference data for fine-tuning. In the reward modeling, we employ a step-wise strategy and incorporate visual constraints into the self-rewarding process to place greater emphasis on visual input. Empirical results demonstrate that CSR enhances performance and reduces hallucinations across ten benchmarks and tasks, achieving substantial improvements over existing methods by 7.62%. Our empirical results are further supported by rigorous theoretical analysis, under mild assumptions, verifying the effectiveness of introducing visual constraints into the self-rewarding paradigm. Additionally, CSR shows compatibility with different vision-language models and the ability to incrementally improve performance through iterative fine-tuning. Our data and code are available at https://github.com/YiyangZhou/CSR.

[Arxiv](https://arxiv.org/abs/2405.14622)