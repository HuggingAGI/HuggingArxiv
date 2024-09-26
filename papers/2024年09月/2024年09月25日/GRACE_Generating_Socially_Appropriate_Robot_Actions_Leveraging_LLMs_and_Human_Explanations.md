# GRACE：借助 LLM 和人类解释，生成符合社会规范的机器人行为

发布时间：2024年09月25日

`Agent` `机器人` `智能家居`

> GRACE: Generating Socially Appropriate Robot Actions Leveraging LLMs and Human Explanations

# 摘要

> 在人类环境中，机器人需处理复杂任务，同时遵守社会规范并适应个人偏好。例如，家用机器人虽知社交聚会期间不宜吸尘，但不确定应在客人到来前还是后来吸尘。此时，结合常识与人类偏好（常通过解释传达）对现有系统颇具挑战。本文提出GRACE，一种生成社会适宜行为的新方法。GRACE利用LLM的常识，通过生成网络架构整合人类解释。其双向结构使机器人能用解释优化LLM预测，并生成人类指定行为的解释。实验表明，整合人类解释显著提升GRACE性能，超越多个基线，并提供合理解释。

> When operating in human environments, robots need to handle complex tasks while both adhering to social norms and accommodating individual preferences. For instance, based on common sense knowledge, a household robot can predict that it should avoid vacuuming during a social gathering, but it may still be uncertain whether it should vacuum before or after having guests. In such cases, integrating common-sense knowledge with human preferences, often conveyed through human explanations, is fundamental yet a challenge for existing systems. In this paper, we introduce GRACE, a novel approach addressing this while generating socially appropriate robot actions. GRACE leverages common sense knowledge from Large Language Models (LLMs), and it integrates this knowledge with human explanations through a generative network architecture. The bidirectional structure of GRACE enables robots to refine and enhance LLM predictions by utilizing human explanations and makes robots capable of generating such explanations for human-specified actions. Our experimental evaluations show that integrating human explanations boosts GRACE's performance, where it outperforms several baselines and provides sensible explanations.

[Arxiv](https://arxiv.org/abs/2409.16879)