# GIVE：基于知识图谱的真实性外推结构化推理

发布时间：2024年10月10日

`LLM应用` `生物医学` `问答系统`

> GIVE: Structured Reasoning with Knowledge Graph Inspired Veracity Extrapolation

# 摘要

> 现有的基于检索的推理方法依赖于非参数知识源的密度和质量，以提供领域知识和显式推理链。然而，构建包容性知识源成本高昂，有时对于科学或边缘领域来说不可行。为此，我们提出了 Graph Inspired Veracity Extrapolation (GIVE)，这是一种新颖的推理框架，它结合参数和非参数记忆，增强稀疏知识图谱上的知识检索和忠实推理。通过利用外部结构化知识，启发 LLM 建模相关概念之间的相互联系，我们的方法促进了一种更逻辑化和逐步的推理方法，类似于专家的问题解决。具体来说，该框架提示 LLM 将查询分解为关键概念和属性，构建包含相关实体的实体组，并通过在这些实体组中的节点对之间探测潜在关系来构建增强的推理链。我们的方法结合了事实和推断的联系，以实现全面的理解和响应生成。在生物医学和常识问答的推理密集型基准上的广泛实验证明了我们方法的有效性。具体来说，GIVE 使 GPT3.5-turbo 在没有额外训练成本的情况下优于 GPT4 等先进模型，从而突显了将结构化信息和 LLM 的内部推理能力集成在一起以应对有限外部资源的专门任务的有效性。

> Existing retrieval-based reasoning approaches for large language models (LLMs) heavily rely on the density and quality of the non-parametric knowledge source to provide domain knowledge and explicit reasoning chain. However, inclusive knowledge sources are expensive and sometimes infeasible to build for scientific or corner domains. To tackle the challenges, we introduce Graph Inspired Veracity Extrapolation (GIVE), a novel reasoning framework that integrates the parametric and non-parametric memories to enhance both knowledge retrieval and faithful reasoning processes on very sparse knowledge graphs. By leveraging the external structured knowledge to inspire LLM to model the interconnections among relevant concepts, our method facilitates a more logical and step-wise reasoning approach akin to experts' problem-solving, rather than gold answer retrieval. Specifically, the framework prompts LLMs to decompose the query into crucial concepts and attributes, construct entity groups with relevant entities, and build an augmented reasoning chain by probing potential relationships among node pairs across these entity groups. Our method incorporates both factual and extrapolated linkages to enable comprehensive understanding and response generation. Extensive experiments on reasoning-intense benchmarks on biomedical and commonsense QA demonstrate the effectiveness of our proposed method. Specifically, GIVE enables GPT3.5-turbo to outperform advanced models like GPT4 without any additional training cost, thereby underscoring the efficacy of integrating structured information and internal reasoning ability of LLMs for tackling specialized tasks with limited external resources.

[Arxiv](https://arxiv.org/abs/2410.08475)