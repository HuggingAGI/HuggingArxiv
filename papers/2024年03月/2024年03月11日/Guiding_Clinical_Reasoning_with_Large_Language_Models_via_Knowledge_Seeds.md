# [借助“知识种子”，我们探索如何有效利用大型语言模型来指导临床推理过程。](https://arxiv.org/abs/2403.06609)

发布时间：2024年03月11日

`LLM应用`

> Guiding Clinical Reasoning with Large Language Models via Knowledge Seeds

> 临床推理是医生诊疗病患的核心思维过程，涉及提议必要检查、诊断疾病及确定疗法等环节，而精准的临床推理依赖于深厚医学知识和丰富实践经验，对医生的要求颇高，尤其在患者众多、医师资源有限的发展中国家，这一难题进一步加剧了全球健康不均衡状况，因此亟需研发自动化临床推理技术。近期，以ChatGPT和GPT-4为代表的大规模语言模型（LLMs）崭露头角，在临床推理领域展现出巨大潜力。但此类LLMs存在“臆想”问题，其推理路径可能与医生的实际临床决策路径不尽相同。为此，我们在本研究中引入一种新颖的框架——上下文填充（ICP），旨在通过植入医学知识强化LLMs的表现力。我们特地挖掘出关键的临床推理元素（即知识种子），并将它们作为参照点引导LLMs的生成过程。实验证明，在两个临床问题数据集上，ICP有效提升了LLMs的临床推理水平。

> Clinical reasoning refers to the cognitive process that physicians employ in evaluating and managing patients. This process typically involves suggesting necessary examinations, diagnosing patients' diseases, and deciding on appropriate therapies, etc. Accurate clinical reasoning requires extensive medical knowledge and rich clinical experience, setting a high bar for physicians. This is particularly challenging in developing countries due to the overwhelming number of patients and limited physician resources, contributing significantly to global health inequity and necessitating automated clinical reasoning approaches. Recently, the emergence of large language models (LLMs) such as ChatGPT and GPT-4 have demonstrated their potential in clinical reasoning. However, these LLMs are prone to hallucination problems, and the reasoning process of LLMs may not align with the clinical decision path of physicians. In this study, we introduce a novel framework, In-Context Padding (ICP), designed to enhance LLMs with medical knowledge. Specifically, we infer critical clinical reasoning elements (referred to as knowledge seeds) and use these as anchors to guide the generation process of LLMs. Experiments on two clinical question datasets demonstrate that ICP significantly improves the clinical reasoning ability of LLMs.