# SANER：一款无需注释的社会属性中和工具，专为消除CLIP中的偏见而设计。

发布时间：2024年08月19日

`LLM应用` `人工智能` `社会科学`

> SANER: Annotation-free Societal Attribute Neutralizer for Debiasing CLIP

# 摘要

> CLIP 等大规模视觉-语言模型存在关于性别、年龄等受保护属性的有害社会偏见。本文旨在解决 CLIP 中的这一问题。虽然以往研究尝试通过对抗学习或测试时投影来去偏，但我们发现存在两大局限：一是输入中明确披露的属性信息丢失，二是在去偏过程中使用属性注释。为此，我们提出 SANER 方法，通过仅从属性中性描述中消除文本特征中的属性信息，有效减轻偏见，同时保留特定属性描述的原始信息，无需属性注释，实验证明其去偏效果优于现有方法。

> Large-scale vision-language models, such as CLIP, are known to contain harmful societal bias regarding protected attributes (e.g., gender and age). In this paper, we aim to address the problems of societal bias in CLIP. Although previous studies have proposed to debias societal bias through adversarial learning or test-time projecting, our comprehensive study of these works identifies two critical limitations: 1) loss of attribute information when it is explicitly disclosed in the input and 2) use of the attribute annotations during debiasing process. To mitigate societal bias in CLIP and overcome these limitations simultaneously, we introduce a simple-yet-effective debiasing method called SANER (societal attribute neutralizer) that eliminates attribute information from CLIP text features only of attribute-neutral descriptions. Experimental results show that SANER, which does not require attribute annotations and preserves original information for attribute-specific descriptions, demonstrates superior debiasing ability than the existing methods.

[Arxiv](https://arxiv.org/abs/2408.10202)