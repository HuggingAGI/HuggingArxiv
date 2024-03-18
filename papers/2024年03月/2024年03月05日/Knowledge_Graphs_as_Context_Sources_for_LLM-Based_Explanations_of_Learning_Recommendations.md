# [在基于LLM的学习推荐解释中，知识图谱可作为重要的上下文信息源。]

发布时间：2024年03月05日

`LLM应用`

> Knowledge Graphs as Context Sources for LLM-Based Explanations of Learning Recommendations

> 在个性化教育的当下，为学习建议配备易懂的解释有助于加深学习者对推荐内容的认知和互动。尽管LLMs和通用生成式AI已崭露头角，能够为人机交互式的推荐学习内容生成类似人类的解释，但在教育这类要求严格的领域，其准确性仍有待提高。为此，本研究提出一种新方法，巧妙地借助知识图谱（KG）作为事实背景来源，引导LLMs生成提示，减少模型臆想输出的可能性，有效防止在生成最终学习解释时出现错误或模糊信息，同时保证贴合实际应用场景的学习语境。我们利用知识图谱内的语义关联，精心提炼出与学习建议相关的知识点。在此过程中，我们携手领域专家共同设计文本模板，由LLM填充完善。在提示构建阶段，我们让领域专家直接参与研究工作，以确保生成的解释切实关联到学习者的需求。最后，我们结合定量指标Rouge-N和Rouge-L进行量化评估，并通过专家和学习者进行定性评测。结果显示，相较于单纯依赖GPT模型生成的解释，我们提出的方案能显著提高生成解释的准确性和召回率，且极大降低了生成不精确信息的风险。

> In the era of personalized education, the provision of comprehensible explanations for learning recommendations is of a great value to enhance the learner's understanding and engagement with the recommended learning content. Large language models (LLMs) and generative AI in general have recently opened new doors for generating human-like explanations, for and along learning recommendations. However, their precision is still far away from acceptable in a sensitive field like education. To harness the abilities of LLMs, while still ensuring a high level of precision towards the intent of the learners, this paper proposes an approach to utilize knowledge graphs (KG) as a source of factual context, for LLM prompts, reducing the risk of model hallucinations, and safeguarding against wrong or imprecise information, while maintaining an application-intended learning context. We utilize the semantic relations in the knowledge graph to offer curated knowledge about learning recommendations. With domain-experts in the loop, we design the explanation as a textual template, which is filled and completed by the LLM. Domain experts were integrated in the prompt engineering phase as part of a study, to ensure that explanations include information that is relevant to the learner. We evaluate our approach quantitatively using Rouge-N and Rouge-L measures, as well as qualitatively with experts and learners. Our results show an enhanced recall and precision of the generated explanations compared to those generated solely by the GPT model, with a greatly reduced risk of generating imprecise information in the final learning explanation.

[Arxiv](https://arxiv.org/abs/2403.03008)