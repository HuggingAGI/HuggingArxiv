# 定义和评估大型语言模型的物理安全性

发布时间：2024年11月04日

`LLM应用` `无人机` `物理安全`

> Defining and Evaluating Physical Safety for Large Language Models

# 摘要

> 大型语言模型（LLM）越来越多地用于控制诸如无人机之类的机器人系统，但它们在现实世界应用中造成身体威胁和伤害的风险仍未得到探索。我们的研究通过为无人机控制开发一个全面的基准来解决评估 LLM 物理安全性方面的关键差距。我们将无人机的物理安全风险分为四类：（1）针对人的威胁，（2）针对物体的威胁，（3）基础设施攻击，（4）违反规定。我们对主流 LLM 的评估揭示了效用和安全性之间的不良权衡，在代码生成方面表现出色的模型在关键安全方面往往表现不佳。此外，虽然结合诸如上下文学习和思维链等先进的提示工程技术可以提高安全性，但这些方法仍然难以识别无意的攻击。另外，较大的模型显示出更好的安全能力，特别是在拒绝危险命令方面。我们的发现和基准可以促进 LLM 物理安全的设计和评估。该项目页面可在 huggingface.co/spaces/TrustSafeAI/LLM-physical-safety 访问。

> Large Language Models (LLMs) are increasingly used to control robotic systems such as drones, but their risks of causing physical threats and harm in real-world applications remain unexplored. Our study addresses the critical gap in evaluating LLM physical safety by developing a comprehensive benchmark for drone control. We classify the physical safety risks of drones into four categories: (1) human-targeted threats, (2) object-targeted threats, (3) infrastructure attacks, and (4) regulatory violations. Our evaluation of mainstream LLMs reveals an undesirable trade-off between utility and safety, with models that excel in code generation often performing poorly in crucial safety aspects. Furthermore, while incorporating advanced prompt engineering techniques such as In-Context Learning and Chain-of-Thought can improve safety, these methods still struggle to identify unintentional attacks. In addition, larger models demonstrate better safety capabilities, particularly in refusing dangerous commands. Our findings and benchmark can facilitate the design and evaluation of physical safety for LLMs. The project page is available at huggingface.co/spaces/TrustSafeAI/LLM-physical-safety.

[Arxiv](https://arxiv.org/abs/2411.02317)