# 重新审视性别歧视与厌女症的分类，聚焦于注释者的态度。

发布时间：2024年10月04日

`LLM应用` `社会科学` `数据分析`

> Re-examining Sexism and Misogyny Classification with Annotator Attitudes

# 摘要

> 基于性别的暴力 (GBV) 在网络空间日益严重，但现有数据集未能全面反映注释者的多样视角，也未能充分代表受影响群体。我们重新审视了 GBV 审核流程中的两个关键环节：手动数据标注和自动分类。在手动标注环节，我们分析了两个数据集，探讨了注释者的身份、态度与其标注结果之间的关系。通过社会心理学领域的三项有效调查，我们收集了众包注释者的人口统计和态度数据。结果显示，右翼威权主义得分越高，将文本标记为性别歧视的倾向越强；而社会支配取向和新性别歧视态度得分越高，这种倾向则越负面。在自动分类环节，我们利用大型语言模型和五种提示策略进行实验，包括在提示中融入注释者信息。实验结果表明：注释者态度显著影响分类器的预测能力；包含态度信息的结构化描述能有效提升分类性能；然而，模型在处理新标签集的复杂性和类别不平衡问题时仍显吃力。

> Gender-Based Violence (GBV) is an increasing problem online, but existing datasets fail to capture the plurality of possible annotator perspectives or ensure the representation of affected groups. We revisit two important stages in the moderation pipeline for GBV: (1) manual data labelling; and (2) automated classification. For (1), we examine two datasets to investigate the relationship between annotator identities and attitudes and the responses they give to two GBV labelling tasks. To this end, we collect demographic and attitudinal information from crowd-sourced annotators using three validated surveys from Social Psychology. We find that higher Right Wing Authoritarianism scores are associated with a higher propensity to label text as sexist, while for Social Dominance Orientation and Neosexist Attitudes, higher scores are associated with a negative tendency to do so. For (2), we conduct classification experiments using Large Language Models and five prompting strategies, including infusing prompts with annotator information. We find: (i) annotator attitudes affect the ability of classifiers to predict their labels; (ii) including attitudinal information can boost performance when we use well-structured brief annotator descriptions; and (iii) models struggle to reflect the increased complexity and imbalanced classes of the new label sets.

[Arxiv](https://arxiv.org/abs/2410.03543)