# SocialGaze：提升大型语言模型中人类社会规范的融合

发布时间：2024年10月11日

`LLM应用` `社会科学` `人工智能伦理`

> SocialGaze: Improving the Integration of Human Social Norms in Large Language Models

# 摘要

> 近年来，尽管许多研究致力于提升大型语言模型（LLM）的推理能力，但这些模型与社会价值观和规范的契合度仍待深入理解。为此，我们提出了“社会接受度判断”任务，要求模型评估并合理化人们在社会情境中的行为是否得当。例如，邻居要求社区成员夜间将宠物留在家中，这一行为是否得体？我们发现，LLM 在此类判断上常与人类共识存在偏差。为解决这一问题，我们设计了 SocialGaze 框架，通过多角度描述社会情境，帮助模型在形成判断前进行全面思考。实验显示，SocialGaze 使 GPT-3.5 模型与人类判断的一致性提升了 11 个 F1 点。此外，我们还揭示了 LLM 在责任分配上的性别和年龄偏见，例如男性更易被不公判断，而年长者的叙述则更易获得模型与人类的一致认可。

> While much research has explored enhancing the reasoning capabilities of large language models (LLMs) in the last few years, there is a gap in understanding the alignment of these models with social values and norms. We introduce the task of judging social acceptance. Social acceptance requires models to judge and rationalize the acceptability of people's actions in social situations. For example, is it socially acceptable for a neighbor to ask others in the community to keep their pets indoors at night? We find that LLMs' understanding of social acceptance is often misaligned with human consensus. To alleviate this, we introduce SocialGaze, a multi-step prompting framework, in which a language model verbalizes a social situation from multiple perspectives before forming a judgment. Our experiments demonstrate that the SocialGaze approach improves the alignment with human judgments by up to 11 F1 points with the GPT-3.5 model. We also identify biases and correlations in LLMs in assigning blame that is related to features such as the gender (males are significantly more likely to be judged unfairly) and age (LLMs are more aligned with humans for older narrators).

[Arxiv](https://arxiv.org/abs/2410.08698)