# 探究大型语言模型在人格引导生成过程中的偏见影响

发布时间：2024年05月30日

`Agent

这篇论文主要关注大型语言模型（LLMs）在角色驱动的文本生成任务中的表现，特别是在处理具有多重特质（不协调角色）的情况下的操控性和观点生成。论文通过比较不同模型在生成反映特定角色个体观点分布的文本时的表现，探讨了模型在处理复杂角色时的局限性和改进方法。此外，论文还讨论了使用人类反馈强化学习（RLHF）微调模型对提高操控性的效果，以及这种微调对角色观点多样性的影响。这些内容涉及到模型的应用和调整，以更好地模拟和反映人类角色的复杂性，因此归类为Agent。` `文本生成` `社会科学`

> Evaluating Large Language Model Biases in Persona-Steered Generation

# 摘要

> 在角色驱动的文本生成任务中，大型语言模型（LLMs）需生成反映特定角色个体观点分布的文本。尽管人的角色多面，但以往研究仅限于多选题或单一维度的角色分析。我们定义了“不协调角色”为具有多重特质的角色，其中某一特质在人类调查数据中降低了其他特质的可能性，如支持增加军费的政治自由主义者。研究发现，LLMs在不协调角色上的操控性比协调角色低9.7%，有时会生成与其人口特征相关的刻板立场而非目标立场。使用人类反馈强化学习（RLHF）微调的模型在操控性上表现更佳，尤其在政治自由主义者和女性相关立场上，但角色观点的多样性显著减少。此外，LLM的可操控性差异无法仅从多选题观点评估中预测。这强调了在开放式文本生成中评估模型的重要性，以揭示新的LLM观点偏见，并探索引导模型展现更丰富、更多样化观点的能力。

> The task of persona-steered text generation requires large language models (LLMs) to generate text that reflects the distribution of views that an individual fitting a persona could have. People have multifaceted personas, but prior work on bias in LLM-generated opinions has only explored multiple-choice settings or one-dimensional personas. We define an incongruous persona as a persona with multiple traits where one trait makes its other traits less likely in human survey data, e.g. political liberals who support increased military spending. We find that LLMs are 9.7% less steerable towards incongruous personas than congruous ones, sometimes generating the stereotypical stance associated with its demographic rather than the target stance. Models that we evaluate that are fine-tuned with Reinforcement Learning from Human Feedback (RLHF) are more steerable, especially towards stances associated with political liberals and women, but present significantly less diverse views of personas. We also find variance in LLM steerability that cannot be predicted from multiple-choice opinion evaluation. Our results show the importance of evaluating models in open-ended text generation, as it can surface new LLM opinion biases. Moreover, such a setup can shed light on our ability to steer models toward a richer and more diverse range of viewpoints.

![探究大型语言模型在人格引导生成过程中的偏见影响](../../../paper_images/2405.20253/x1.png)

![探究大型语言模型在人格引导生成过程中的偏见影响](../../../paper_images/2405.20253/x2.png)

![探究大型语言模型在人格引导生成过程中的偏见影响](../../../paper_images/2405.20253/x3.png)

![探究大型语言模型在人格引导生成过程中的偏见影响](../../../paper_images/2405.20253/interface.png)

[Arxiv](https://arxiv.org/abs/2405.20253)