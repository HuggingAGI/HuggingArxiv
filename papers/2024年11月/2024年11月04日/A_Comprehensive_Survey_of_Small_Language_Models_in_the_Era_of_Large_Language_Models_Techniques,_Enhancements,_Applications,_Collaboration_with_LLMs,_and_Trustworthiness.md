# 在大型语言模型时代小型语言模型的综合调查：技术、增强、应用、与大型语言模型的协作以及可信度

发布时间：2024年11月04日

`LLM应用`

> A Comprehensive Survey of Small Language Models in the Era of Large Language Models: Techniques, Enhancements, Applications, Collaboration with LLMs, and Trustworthiness

# 摘要

> 摘要：大型语言模型（LLM）在文本生成、问答和推理方面展现出了新兴能力，为各种任务和领域提供了便利。尽管它们在各种任务中表现出色，但像 LaPM 540B 和 Llama-3.1 405B 这样的 LLM 由于参数规模大、计算需求高，往往需要使用云 API，这引发了隐私问题，限制了在边缘设备上的实时应用，并增加了微调成本。此外，由于特定领域知识不足，LLM 在医疗保健和法律等专业领域的表现往往不佳，因此需要专门的模型。因此，小型语言模型（SLM）因其低推理延迟、成本效益高、开发高效以及易于定制和适应而越来越受到青睐。这些模型特别适用于资源有限的环境和领域知识获取，解决了 LLM 的挑战，并被证明是需要为隐私进行本地化数据处理、为效率实现最小推理延迟以及通过轻量级微调获取领域知识的应用的理想选择。对 SLM 的需求不断增加，推动了广泛的研究和开发。然而，目前仍缺乏对与 SLM 的定义、获取、应用、增强和可靠性相关问题的全面调查，这促使我们对这些主题进行详细的调查。SLM 的定义差异很大，因此为了标准化，我们建议根据其执行专门任务的能力和对资源受限环境的适用性来定义 SLM，根据新兴能力的最小规模和资源约束下可持续的最大规模来设定界限。对于其他方面，我们提供了相关模型/方法的分类，并为每个类别开发了通用框架，以有效增强和利用 SLM。

> 
Abstract:Large language models (LLM) have demonstrated emergent abilities in text generation, question answering, and reasoning, facilitating various tasks and domains. Despite their proficiency in various tasks, LLMs like LaPM 540B and Llama-3.1 405B face limitations due to large parameter sizes and computational demands, often requiring cloud API use which raises privacy concerns, limits real-time applications on edge devices, and increases fine-tuning costs. Additionally, LLMs often underperform in specialized domains such as healthcare and law due to insufficient domain-specific knowledge, necessitating specialized models. Therefore, Small Language Models (SLMs) are increasingly favored for their low inference latency, cost-effectiveness, efficient development, and easy customization and adaptability. These models are particularly well-suited for resource-limited environments and domain knowledge acquisition, addressing LLMs' challenges and proving ideal for applications that require localized data handling for privacy, minimal inference latency for efficiency, and domain knowledge acquisition through lightweight fine-tuning. The rising demand for SLMs has spurred extensive research and development. However, a comprehensive survey investigating issues related to the definition, acquisition, application, enhancement, and reliability of SLM remains lacking, prompting us to conduct a detailed survey on these topics. The definition of SLMs varies widely, thus to standardize, we propose defining SLMs by their capability to perform specialized tasks and suitability for resource-constrained settings, setting boundaries based on the minimal size for emergent abilities and the maximum size sustainable under resource constraints. For other aspects, we provide a taxonomy of relevant models/methods and develop general frameworks for each category to enhance and utilize SLMs effectively.
    

[Arxiv](https://arxiv.org/pdf/2411.03350)