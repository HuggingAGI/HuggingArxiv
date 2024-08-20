# 利用实例级 LoRA 技术，个性化定制语言模型，以优化顺序推荐效果。

发布时间：2024年08月19日

`LLM应用` `电子商务`

> Customizing Language Models with Instance-wise LoRA for Sequential Recommendation

# 摘要

> 顺序推荐系统通过分析用户过往行为，精准预测其下一个兴趣点，与个人喜好紧密契合。近期，借助大型语言模型（LLM）在知识理解和推理上的强大能力，研究者们通过语言生成范式，将LLM应用于推荐系统，将用户行为序列转化为LLM微调的提示，并采用低秩适应（LoRA）模块优化推荐。然而，LoRA在处理多样用户行为时，有时未能充分捕捉个体差异，导致性能欠佳及序列间的不良影响。为此，我们创新提出实例化LoRA（iLoRA），结合专家混合（MoE）框架，构建一系列专家，各司其职捕捉用户偏好特定层面，并设计序列表示引导门函数，处理历史交互，生成丰富表示，引导门网络输出个性化专家权重，从而精准应对，动态适应行为多样性，有效减少不良影响。实验结果显示，iLoRA在三大基准数据集上表现卓越，显著提升用户特定偏好的捕捉能力及推荐准确性，超越现有方法。

> Sequential recommendation systems predict a user's next item of interest by analyzing past interactions, aligning recommendations with individual preferences. Leveraging the strengths of Large Language Models (LLMs) in knowledge comprehension and reasoning, recent approaches have applied LLMs to sequential recommendation through language generation paradigms. These methods convert user behavior sequences into prompts for LLM fine-tuning, utilizing Low-Rank Adaptation (LoRA) modules to refine recommendations. However, the uniform application of LoRA across diverse user behaviors sometimes fails to capture individual variability, leading to suboptimal performance and negative transfer between disparate sequences. To address these challenges, we propose Instance-wise LoRA (iLoRA), integrating LoRA with the Mixture of Experts (MoE) framework. iLoRA creates a diverse array of experts, each capturing specific aspects of user preferences, and introduces a sequence representation guided gate function. This gate function processes historical interaction sequences to generate enriched representations, guiding the gating network to output customized expert participation weights. This tailored approach mitigates negative transfer and dynamically adjusts to diverse behavior patterns. Extensive experiments on three benchmark datasets demonstrate the effectiveness of iLoRA, highlighting its superior performance compared to existing methods in capturing user-specific preferences and improving recommendation accuracy.

[Arxiv](https://arxiv.org/abs/2408.10159)