# 大型语言模型处理：自然语言条件下的数值预测分布

发布时间：2024年05月21日

`LLM应用

这篇论文主要探讨了如何利用大型语言模型（LLMs）来整合用户的自然语言先验知识，以指导数值数据的概率预测。这种方法涉及从LLMs中提取明确的数值预测分布，并在多种场景中应用这些预测，如预测、多维回归、优化和图像建模。论文的研究重点是如何通过提示来引出一致的预测分布，并验证其在回归任务中的有效性。此外，论文还展示了如何将文本融入数值预测，以提升预测准确性，并赋予定量结构以反映定性描述。这些内容直接关联到LLM的应用层面，因此将其分类为LLM应用。` `机器学习`

> LLM Processes: Numerical Predictive Distributions Conditioned on Natural Language

# 摘要

> 机器学习实践者在整合先验知识到预测模型时面临挑战，限制了上下文敏感分析的深度。通常，这种整合需要专业技能，使得模型应用局限于专家。我们的目标是开发一个回归模型，能处理数值数据，并在任意位置进行概率预测，这些预测由用户的自然语言先验知识指导。大型语言模型（LLMs）为此提供了基础，因为它们允许用户以自然语言输入专家见解，并利用LLMs中潜在的相关问题知识。我们首先研究如何从LLMs中提取明确的数值预测分布，这些分布在多种场景中，如预测、多维回归、优化和图像建模中，对任意数量的变量进行预测。我们探讨了如何通过提示来引出一致的预测分布，并验证了其在回归任务中的有效性。最终，我们展示了如何将文本融入数值预测，提升预测准确性，并赋予定量结构以反映定性描述，从而开启了探索LLMs隐含的丰富假设空间的大门。

> Machine learning practitioners often face significant challenges in formally integrating their prior knowledge and beliefs into predictive models, limiting the potential for nuanced and context-aware analyses. Moreover, the expertise needed to integrate this prior knowledge into probabilistic modeling typically limits the application of these models to specialists. Our goal is to build a regression model that can process numerical data and make probabilistic predictions at arbitrary locations, guided by natural language text which describes a user's prior knowledge. Large Language Models (LLMs) provide a useful starting point for designing such a tool since they 1) provide an interface where users can incorporate expert insights in natural language and 2) provide an opportunity for leveraging latent problem-relevant knowledge encoded in LLMs that users may not have themselves. We start by exploring strategies for eliciting explicit, coherent numerical predictive distributions from LLMs. We examine these joint predictive distributions, which we call LLM Processes, over arbitrarily-many quantities in settings such as forecasting, multi-dimensional regression, black-box optimization, and image modeling. We investigate the practical details of prompting to elicit coherent predictive distributions, and demonstrate their effectiveness at regression. Finally, we demonstrate the ability to usefully incorporate text into numerical predictions, improving predictive performance and giving quantitative structure that reflects qualitative descriptions. This lets us begin to explore the rich, grounded hypothesis space that LLMs implicitly encode.

[Arxiv](https://arxiv.org/abs/2405.12856)