# 大型语言模型在评估代理对开放式请求响应中的约束满足方面展现出独特能力。

发布时间：2024年09月22日

`LLM应用` `食品与营养` `人工智能`

> The Ability of Large Language Models to Evaluate Constraint-satisfaction in Agent Responses to Open-ended Requests

# 摘要

> 生成式AI代理常需应对“无唯一正确答案”（NORA）的复杂请求，如“设计一份低于1800卡路里的素食餐计划”。这类请求包含代理需遵守的约束条件。为开发适用于NORA场景的代理，一个能验证响应中约束条件满足情况的自动评估框架至关重要。尽管大型语言模型（LLMs）已被用于评估许多NORA任务，但其评估生成文本中约束条件满足情况的能力尚不明确。为此，我们推出新的算术约束满足（ACS）基准数据集，包含复杂请求、相应约束、代理响应及人工标签，指示每个约束的满足程度。该数据集独特之处在于，验证约束需全面审查响应，而非仅验证单个项目。此外，它评估LLMs在推理、数据提取、算术计算和计数方面的能力。基准测试显示，大多数LLMs在评估约束满足情况方面仍有显著改进空间，错误多源于推理问题。此外，模型在预测约束满足情况时存在偏差，尤其在地面实况标签为“满足”时准确性较高。最后，少样本提示对许多模型而言颇具挑战，引入后性能有所下降。

> Generative AI agents are often expected to respond to complex user requests that have No One Right Answer (NORA), e.g., "design a vegetarian meal plan below 1800 calories". Such requests may entail a set of constraints that the agent should adhere to. To successfully develop agents for NORA scenarios, an accurate automatic evaluation framework is essential, and specifically - one capable of validating the satisfaction of constraints in the agent's response. Recently, large language models (LLMs) have been adopted as versatile evaluators for many NORA tasks, but their ability to evaluate constraint-satisfaction in generated text remains unclear. To study this, we develop and release a novel Arithmetic Constraint-Satisfaction (ACS) benchmarking dataset. The dataset consists of complex user requests with corresponding constraints, agent responses and human labels indicating each constraint's satisfaction level in the response. A unique property of this dataset is that validating many of its constraints requires reviewing the response as a whole (in contrast to many other benchmarks that require the validation of a single independent item). Moreover, it assesses LLMs in performing reasoning, in-context data extraction, arithmetic calculations, and counting. We then benchmark both open and proprietary LLMs on evaluating constraint-satisfaction, and show that most models still have a significant headroom for improvement, and that errors primarily stem from reasoning issues. In addition, most models exhibit a skewed constraint-satisfaction prediction pattern, with higher accuracy where the ground-truth label is "satisfied". Lastly, few-shot prompting for our task proved to be rather challenging, since many of the studied models showed a degradation in performance when it was introduced.

[Arxiv](https://arxiv.org/abs/2409.14371)