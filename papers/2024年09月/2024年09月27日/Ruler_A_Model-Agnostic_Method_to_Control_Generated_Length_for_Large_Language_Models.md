# Ruler：一种与模型无关的方法，专为控制大型语言模型的生成长度而设计

发布时间：2024年09月27日

`LLM应用` `人工智能`

> Ruler: A Model-Agnostic Method to Control Generated Length for Large Language Models

# 摘要

> 大型语言模型（LLM）的指令遵循能力让AI与人类的互动更加自然。然而，在生成特定长度的响应时，LLM往往因难以准确把握数值限制而难以满足用户需求。为此，我们提出了目标长度生成任务（TLG），并设计了精确匹配（PM）和灵活匹配（FM）两个指标，以评估模型在遵守响应长度要求方面的表现。我们还引入了一种名为Ruler的创新方法，通过使用元长度标记（MLT）来增强LLM在长度约束指令下的表现。Ruler不仅能让LLM根据指令中的长度约束生成相应长度的响应，还能在没有明确长度约束时自动生成合适的MLT，展现出卓越的灵活性和泛化能力。实验结果表明，Ruler在不同LLM上的TLG任务中表现出色，例如在PM和FM上分别获得了27.97和29.57的平均增益。此外，通过广泛的消融实验，我们进一步验证了Ruler的有效性和广泛适用性。相关代码和数据已公开在https://github.com/Geaming2002/Ruler。

> The instruction-following ability of large language models enables humans to interact with AI agents in a natural way. However, when required to generate responses of a specific length, large language models often struggle to meet users' needs due to their inherent difficulty in accurately perceiving numerical constraints. To explore the ability of large language models to control the length of generated responses, we propose the Target Length Generation Task (TLG) and design two metrics, Precise Match (PM) and Flexible Match (FM) to evaluate the model's performance in adhering to specified response lengths. Furthermore, we introduce a novel, model-agnostic approach called Ruler, which employs Meta Length Tokens (MLTs) to enhance the instruction-following ability of large language models under length-constrained instructions. Specifically, Ruler equips LLMs with the ability to generate responses of a specified length based on length constraints within the instructions. Moreover, Ruler can automatically generate appropriate MLT when length constraints are not explicitly provided, demonstrating excellent versatility and generalization. Comprehensive experiments show the effectiveness of Ruler across different LLMs on Target Length Generation Task, e.g., at All Level 27.97 average gain on PM, 29.57 average gain on FM. In addition, we conduct extensive ablation experiments to further substantiate the efficacy and generalization of Ruler. Our code and data is available at https://github.com/Geaming2002/Ruler.

[Arxiv](https://arxiv.org/abs/2409.18943)