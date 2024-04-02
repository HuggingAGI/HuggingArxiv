# 辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险

发布时间：2024年03月30日

`LLM理论` `人工智能` `安全与隐私`

> Dialectical Alignment: Resolving the Tension of 3H and Security Threats of LLMs

# 摘要

> 随着大型语言模型（LLMs）的流行，让它们遵循有用、诚实和无害（3H）的原则，即人类对齐，显得尤为重要。然而，现有的对齐技术，例如RLHF、DPO等，虽然能有效调整LLMs以符合偏好数据集中的设定，却也使模型对人类输入和外部信息过于敏感，哪怕这些信息包含误导。这让LLMs在面对与内置记忆相冲突的外部证据时，容易变得像适应性变色龙。这种现象增加了LLM受到恶意数据攻击的风险，给如检索增强生成（RAG）等LLM系统应用带来安全隐患。为此，我们提出了一种新的框架——辩证对齐（DA），它通过AI反馈找出LLMs在面对不同外部证据时解决上下文冲突的最佳策略，构建相应的SFT和偏好数据集，并利用这些数据集进行LLM对齐，既抵御恶意上下文攻击，又保持上下文知识编辑的效果。实验显示，辩证对齐模型显著提升了对恶意数据攻击的防御能力，且无需额外的提示设计或提前告知LLMs可能遭受攻击。

> With the rise of large language models (LLMs), ensuring they embody the principles of being helpful, honest, and harmless (3H), known as Human Alignment, becomes crucial. While existing alignment methods like RLHF, DPO, etc., effectively fine-tune LLMs to match preferences in the preference dataset, they often lead LLMs to highly receptive human input and external evidence, even when this information is poisoned. This leads to a tendency for LLMs to be Adaptive Chameleons when external evidence conflicts with their parametric memory. This exacerbates the risk of LLM being attacked by external poisoned data, which poses a significant security risk to LLM system applications such as Retrieval-augmented generation (RAG). To address the challenge, we propose a novel framework: Dialectical Alignment (DA), which (1) utilizes AI feedback to identify optimal strategies for LLMs to navigate inter-context conflicts and context-memory conflicts with different external evidence in context window (i.e., different ratios of poisoned factual contexts); (2) constructs the SFT dataset as well as the preference dataset based on the AI feedback and strategies above; (3) uses the above datasets for LLM alignment to defense poisoned context attack while preserving the effectiveness of in-context knowledge editing. Our experiments show that the dialectical alignment model improves poisoned data attack defense by 20 and does not require any additional prompt engineering or prior declaration of ``you may be attacked`` to the LLMs' context window.

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x1.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x2.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x3.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x4.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x5.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x6.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x7.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x8.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x9.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x10.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x11.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x12.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x13.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x14.png)

![辩证对齐：平衡人类福祉、人类价值和大型语言模型的安全风险](../../../paper_images/2404.00486/x15.png)

[Arxiv](https://arxiv.org/abs/2404.00486)