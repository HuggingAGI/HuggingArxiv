# 代理 LLM 工作流程助力生成患者友好型医疗报告

发布时间：2024年08月02日

`Agent` `人工智能`

> Agentic LLM Workflows for Generating Patient-Friendly Medical Reports

# 摘要

> 大型语言模型在医疗领域的应用日益广泛，其中一项创新是将专业医疗报告转化为患者易懂的版本。目前，这些模型的输出往往需要人工校验和编辑，以确保信息的准确性和易懂性。为此，我们提出了一种基于 Reflexion 框架的代理工作流程，通过迭代自我反思机制来优化模型输出。在测试中，我们对比了该方法与传统的零-shot 提示法在16份放射学报告上的表现。结果显示，采用多代理方法的报告在 ICD-10 代码验证上的准确率高达 94.94%，远超零-shot 提示法的 68.23%。更令人鼓舞的是，81.25% 的反思报告无需进一步修正，而零-shot 提示法仅能满足这一标准的 25%。这些成果表明，我们的方法不仅高效、连贯，而且能确保医疗信息的准确传达。所有相关代码已公开，供公众查阅。

> The application of Large Language Models (LLMs) in healthcare is expanding rapidly, with one potential use case being the translation of formal medical reports into patient-legible equivalents. Currently, LLM outputs often need to be edited and evaluated by a human to ensure both factual accuracy and comprehensibility, and this is true for the above use case. We aim to minimize this step by proposing an agentic workflow with the Reflexion framework, which uses iterative self-reflection to correct outputs from an LLM. This pipeline was tested and compared to zero-shot prompting on 16 randomized radiology reports. In our multi-agent approach, reports had an accuracy rate of 94.94% when looking at verification of ICD-10 codes, compared to zero-shot prompted reports, which had an accuracy rate of 68.23%. Additionally, 81.25% of the final reflected reports required no corrections for accuracy or readability, while only 25% of zero-shot prompted reports met these criteria without needing modifications. These results indicate that our approach presents a feasible method for communicating clinical findings to patients in a quick, efficient and coherent manner whilst also retaining medical accuracy. All code is available for viewing at http://github.com/malavikhasudarshan/Multi-Agent-Patient-Letter-Generation.

[Arxiv](https://arxiv.org/abs/2408.01112)