# HuixiangDou-CR：群组聊天中的同指识别技术

发布时间：2024年05月05日

`LLM应用` `对话系统`

> HuixiangDou-CR: Coreference Resolution in Group Chats

# 摘要

> 我们如何避免群聊中的代词混淆？本研究中，我们对5.8万条真实对话记录进行了预处理，并精心标注了2300个问题，其准确性得到了扩展法则的验证。随后，我们在参数规模从5亿到320亿的Qwen模型上执行了精细调整，最佳模型在F1分数上实现了29.07%的提升，从而验证了对大型语言模型（LLM）进行微调以适应下游自然语言处理（NLP）任务的高效性。我们的成果包括：1）开发了以羊驼格式的监督式微调（SFT）训练集和一套低秩适应（LoRA）权重；2）设计了一种基于扩展法则原则获取优质数据的方法。相关脚本、原始数据以及实验记录已在Github、HuggingFace和WandB平台开源。用户已授权所涉数据的隐私使用。

> How to eliminate pronominal reference in group chats? In this work, we have preprocessed 58k authentic chat data and manually annotated 2.3k questions. The reliability of this annotation was confirmed by the scaling law. After this, we conducted fine-tuning on Qwen models, ranging from 0.5B to 32B parameters. The optimal version improved 29.07 in F1 score. This confirms the viability of fine-tuning Large Language Model (LLM) for downstream Natural Language Processing (NLP) tasks. Our contributions are: 1) Created Supervised Fine-Tuning (SFT) training data in alpaca format, along with a set of Low-Rank Adaptation (LoRA) weights, and 2) Developed a method for acquiring high-quality data leveraging scaling law principle. The script, raw data with alpaca format and experiments track are open-sourced on Github https://github.com/InternLM/HuixiangDou/tree/main/web/tools, HuggingFace https://huggingface.co/tpoisonooo and WandB https://wandb.ai/tpoisonooo/huixiangdou-cr/table?nw=nwusertpoisonooo . The privacy of the data involved has been authorized by users.

![HuixiangDou-CR：群组聊天中的同指识别技术](../../../paper_images/2405.02817/annotation.png)

![HuixiangDou-CR：群组聊天中的同指识别技术](../../../paper_images/2405.02817/qwen4-loss.png)

![HuixiangDou-CR：群组聊天中的同指识别技术](../../../paper_images/2405.02817/overall.png)

[Arxiv](https://arxiv.org/abs/2405.02817)