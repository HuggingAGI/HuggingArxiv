# XAgents：一个用于实现可解释的基于规则的多智能体合作的框架

发布时间：2024年11月21日

`Agent` `多智能体系统` `可解释性框架`

> XAgents: A Framework for Interpretable Rule-Based Multi-Agents Cooperation

# 摘要

> 从大型语言模型（LLMs）中提取隐性知识和逻辑推理能力始终是一项重大挑战。多智能体系统的发展进一步提升了LLMs的能力。受多极神经元（MNs）结构的启发，我们提出了XAgents框架，这是一个基于IF-THEN规则系统的可解释多智能体协作框架。规则的IF部分负责逻辑推理和领域成员资格的计算，THEN部分则由生成特定领域内容的领域专家代理构成。完成成员资格的计算后，XAgents将任务传递给不同的领域规则，进而生成各种响应。这些响应类似于不同专家针对同一问题给出的答案。通过成员资格计算以及各领域规则的语义对抗生成，消除LLM的幻觉和错误知识，从而得出最终响应。规则可解释性的融入增强了用户对XAgents框架的信心。我们通过与最新的AutoAgents进行对比分析来评估XAgents的效果，XAgents在三个不同的数据集中均展现出卓越的性能。我们运用SHAP算法和案例研究开展事后可解释性研究，证明了XAgent在输入输出特征关联和基于规则的语义方面具有可解释性。

> Extracting implicit knowledge and logical reasoning abilities from large language models (LLMs) has consistently been a significant challenge. The advancement of multi-agent systems has further en-hanced the capabilities of LLMs. Inspired by the structure of multi-polar neurons (MNs), we propose the XAgents framework, an in-terpretable multi-agent cooperative framework based on the IF-THEN rule-based system. The IF-Parts of the rules are responsible for logical reasoning and domain membership calculation, while the THEN-Parts are comprised of domain expert agents that generate domain-specific contents. Following the calculation of the member-ship, XAgetns transmits the task to the disparate domain rules, which subsequently generate the various responses. These re-sponses are analogous to the answers provided by different experts to the same question. The final response is reached at by eliminat-ing the hallucinations and erroneous knowledge of the LLM through membership computation and semantic adversarial genera-tion of the various domain rules. The incorporation of rule-based interpretability serves to bolster user confidence in the XAgents framework. We evaluate the efficacy of XAgents through a com-parative analysis with the latest AutoAgents, in which XAgents demonstrated superior performance across three distinct datasets. We perform post-hoc interpretable studies with SHAP algorithm and case studies, proving the interpretability of XAgent in terms of input-output feature correlation and rule-based semantics.

[Arxiv](https://arxiv.org/abs/2411.13932)