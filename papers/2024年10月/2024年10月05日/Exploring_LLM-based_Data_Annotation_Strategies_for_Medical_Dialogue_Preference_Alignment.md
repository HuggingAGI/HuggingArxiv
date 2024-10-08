# 探索基于大型语言模型的数据标注策略，以实现医疗对话中的偏好对齐

发布时间：2024年10月05日

`LLM应用` `人工智能`

> Exploring LLM-based Data Annotation Strategies for Medical Dialogue Preference Alignment

# 摘要

> 本研究利用 AI 反馈强化学习 (RLAIF) 技术，旨在改进医疗对话模型，同时减少对医疗专家的依赖。我们发现，当前 RLAIF 在医疗领域的主要难题在于自动化评估的局限性和准确表达医生偏好的困难。为此，我们设计了一个基于标准化患者检查的评估框架，以客观衡量 LLM 在指导和遵循指令方面的表现，便于模型间的全面对比。通过研究宪法 AI 算法，我们发现流程图在表达医生偏好方面尤为有效。基于此，我们开发了一种创新的代理注释方法，该方法能自主生成符合患者情况的对话流程，具备强大的泛化能力，并显著减少专家介入。实验结果显示，该方法在标准化患者检查中表现优异，超越了现有的 RLAIF 注释技术和开源医疗对话 LLM。

> This research examines the use of Reinforcement Learning from AI Feedback (RLAIF) techniques to improve healthcare dialogue models, with the aim of tackling the challenges of preference-aligned data annotation while reducing the reliance on medical experts. We argue that the primary challenges in current RLAIF research for healthcare are the limitations of automated evaluation methods and the difficulties in accurately representing physician preferences. To address these challenges, we present a new evaluation framework based on standardized patient examinations. This framework is designed to objectively assess the effectiveness of large language models (LLMs) in guiding users and following instructions, enabling a comprehensive comparison across different models. Furthermore, our investigation of effective ways to express physician preferences using Constitutional AI algorithms highlighted the particular effectiveness of flowcharts. Utilizing this finding, we introduce an innovative agent-based approach for annotating preference data. This approach autonomously creates medical dialogue flows tailored to the patient's condition, demonstrates strong generalization abilities, and reduces the need for expert involvement. Our results show that the agent-based approach outperforms existing RLAIF annotation methods in standardized patient examinations and surpasses current open source medical dialogue LLMs in various test scenarios.

[Arxiv](https://arxiv.org/abs/2410.04112)