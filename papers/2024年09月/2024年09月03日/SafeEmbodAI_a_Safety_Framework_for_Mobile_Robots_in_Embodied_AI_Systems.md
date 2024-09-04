# SafeEmbodAI：为具身AI系统中的移动机器人量身打造的安全框架

发布时间：2024年09月03日

`LLM应用` `机器人` `人工智能`

> SafeEmbodAI: a Safety Framework for Mobile Robots in Embodied AI Systems

# 摘要

> 具身AI系统，如自主操作的AI机器人，得益于大型语言模型（LLMs），能更精准地理解复杂指令并执行高级任务，显著提升其能力。然而，这也带来了安全风险，尤其是在机器人导航中。不当的安全措施可能导致系统在复杂环境中失效，甚至遭受恶意指令攻击，引发危险行为。为此，我们设计了\textit{SafeEmbodAI}框架，通过安全提示、状态管理和安全验证，确保LLMs在处理多模态数据时的安全与准确。我们的评估显示，该框架能有效抵御恶意攻击，提升系统在多样环境中的性能，保障具身AI的安全。特别是在复杂环境中，我们的方法在应对攻击时性能提升了267\%，展现了其强大的适应性和鲁棒性。

> Embodied AI systems, including AI-powered robots that autonomously interact with the physical world, stand to be significantly advanced by Large Language Models (LLMs), which enable robots to better understand complex language commands and perform advanced tasks with enhanced comprehension and adaptability, highlighting their potential to improve embodied AI capabilities. However, this advancement also introduces safety challenges, particularly in robotic navigation tasks. Improper safety management can lead to failures in complex environments and make the system vulnerable to malicious command injections, resulting in unsafe behaviours such as detours or collisions. To address these issues, we propose \textit{SafeEmbodAI}, a safety framework for integrating mobile robots into embodied AI systems. \textit{SafeEmbodAI} incorporates secure prompting, state management, and safety validation mechanisms to secure and assist LLMs in reasoning through multi-modal data and validating responses. We designed a metric to evaluate mission-oriented exploration, and evaluations in simulated environments demonstrate that our framework effectively mitigates threats from malicious commands and improves performance in various environment settings, ensuring the safety of embodied AI systems. Notably, In complex environments with mixed obstacles, our method demonstrates a significant performance increase of 267\% compared to the baseline in attack scenarios, highlighting its robustness in challenging conditions.

[Arxiv](https://arxiv.org/abs/2409.01630)