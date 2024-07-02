# 利用强化学习优化查询，提升大型语言模型的性能与稳定性

发布时间：2024年07月01日

`LLM应用` `人工智能` `网络安全`

> Enhancing the Capability and Robustness of Large Language Models through Reinforcement Learning-Driven Query Refinement

# 摘要

> 大型语言模型（LLM）的回应质量深受用户提示的影响，但这些提示往往简短且模糊，限制了LLM的潜力。此外，恶意用户可能精心设计有害提示，试图破解LLM，导致其输出有害内容。为提升LLM的性能并增强其对抗恶意输入的鲁棒性，本研究提出了一种灵活的框架，用于优化用户提示。该框架通过提升查询质量，使LLM生成更真实、无害且有用的回应。我们引入了一个轻量级模型，采用创新的强化学习方法进行训练，旨在强化LLM的特定能力。实验证明，该模型不仅提升了回应质量，还增强了其抵御破解攻击的能力。相关代码已公开，详见：https://github.com/Huangzisu/query-refinement。

> The capacity of large language models (LLMs) to generate honest, harmless, and helpful responses heavily relies on the quality of user prompts. However, these prompts often tend to be brief and vague, thereby significantly limiting the full potential of LLMs. Moreover, harmful prompts can be meticulously crafted and manipulated by adversaries to jailbreak LLMs, inducing them to produce potentially toxic content. To enhance the capabilities of LLMs while maintaining strong robustness against harmful jailbreak inputs, this study proposes a transferable and pluggable framework that refines user prompts before they are input into LLMs. This strategy improves the quality of the queries, empowering LLMs to generate more truthful, benign and useful responses. Specifically, a lightweight query refinement model is introduced and trained using a specially designed reinforcement learning approach that incorporates multiple objectives to enhance particular capabilities of LLMs. Extensive experiments demonstrate that the refinement model not only improves the quality of responses but also strengthens their robustness against jailbreak attacks. Code is available at: https://github.com/Huangzisu/query-refinement .

![利用强化学习优化查询，提升大型语言模型的性能与稳定性](../../../paper_images/2407.01461/x1.png)

![利用强化学习优化查询，提升大型语言模型的性能与稳定性](../../../paper_images/2407.01461/x2.png)

![利用强化学习优化查询，提升大型语言模型的性能与稳定性](../../../paper_images/2407.01461/x3.png)

![利用强化学习优化查询，提升大型语言模型的性能与稳定性](../../../paper_images/2407.01461/x4.png)

![利用强化学习优化查询，提升大型语言模型的性能与稳定性](../../../paper_images/2407.01461/x5.png)

[Arxiv](https://arxiv.org/abs/2407.01461)