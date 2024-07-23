# 大型语言模型在机器翻译中实现细粒度性别控制

发布时间：2024年07月21日

`LLM应用` `机器翻译` `人工智能`

> Fine-grained Gender Control in Machine Translation with Large Language Models

# 摘要

> 在机器翻译领域，模糊性别输入的问题已被指出，即源句中实体性别信息缺失。为解决这一难题，受控翻译任务应运而生，它将模糊实体的性别作为额外输入。然而，现有研究多局限于单一目标性别的简化场景。本文中，我们挑战更贴近现实的复杂场景，即输入包含多个实体，并创新性地提出实体性别（GoE）提示方法，指导LLM利用精细的实体级性别信息进行准确翻译。通过四大评估基准的检验，我们深入探究了LLM在多维度上的受控翻译实力，并发现其在该领域已达到顶尖水平。同时，我们观察到控制多实体性别时出现的性别干扰现象。最后，针对现有性别准确性评估指标的不足，我们提出利用LLM作为机器翻译中性别屈折的评估工具，以期推动该领域的进一步发展。

> In machine translation, the problem of ambiguously gendered input has been pointed out, where the gender of an entity is not available in the source sentence. To address this ambiguity issue, the task of controlled translation that takes the gender of the ambiguous entity as additional input have been proposed. However, most existing works have only considered a simplified setup of one target gender for input. In this paper, we tackle controlled translation in a more realistic setting of inputs with multiple entities and propose Gender-of-Entity (GoE) prompting method for LLMs. Our proposed method instructs the model with fine-grained entity-level gender information to translate with correct gender inflections. By utilizing four evaluation benchmarks, we investigate the controlled translation capability of LLMs in multiple dimensions and find that LLMs reach state-of-the-art performance in controlled translation. Furthermore, we discover an emergence of gender interference phenomenon when controlling the gender of multiple entities. Finally, we address the limitations of existing gender accuracy evaluation metrics and propose leveraging LLMs as an evaluator for gender inflection in machine translation.

![大型语言模型在机器翻译中实现细粒度性别控制](../../../paper_images/2407.15154/x1.png)

![大型语言模型在机器翻译中实现细粒度性别控制](../../../paper_images/2407.15154/x2.png)

![大型语言模型在机器翻译中实现细粒度性别控制](../../../paper_images/2407.15154/humaneval.png)

[Arxiv](https://arxiv.org/abs/2407.15154)