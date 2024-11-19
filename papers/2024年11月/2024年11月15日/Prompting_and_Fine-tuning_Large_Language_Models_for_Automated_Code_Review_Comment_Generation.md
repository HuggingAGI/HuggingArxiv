# 通过提示和微调大型语言模型来实现自动代码审查评论的生成

发布时间：2024年11月15日

`LLM应用` `软件开发` `代码审查`

> Prompting and Fine-tuning Large Language Models for Automated Code Review Comment Generation

# 摘要

> 生成准确的代码审查评论一直是个重大挑战，毕竟任务输出天然具有多样性和非唯一性。在编程和自然语言数据上预训练的大型语言模型，在面向代码的任务中通常表现出色。但由于对环境的影响以及项目特定的通用性问题，大规模预训练并非总是可行。在本研究中，我们先是在消费级硬件上以参数高效、量化低秩（QLoRA）的方式对开源大型语言模型（LLM）进行微调，以优化审查评论的生成。近期研究显示，在提示中加入语义元数据信息能提升其他代码相关任务的性能。为在代码审查活动中探究此点，我们还提示专有的、闭源的LLM，将输入的代码补丁与函数调用图和代码摘要相结合进行增强。我们的这两种策略都提升了审查评论的生成性能，在GPT-3.5模型上，基于函数调用图增强的少样本提示在CodeReviewer数据集上的BLEU-4得分比预训练基线高出约90%。此外，少样本提示的Gemini-1.0 Pro、QLoRA微调的Code Llama和Llama 3.1模型在该任务上也取得了颇具竞争力的结果（性能提升幅度在25%至83%之间）。另外的一项人类评估研究进一步证实了我们的实验发现，反映了现实世界中开发者基于相关定性指标对LLM生成的代码审查评论的看法。

> Generating accurate code review comments remains a significant challenge due to the inherently diverse and non-unique nature of the task output. Large language models pretrained on both programming and natural language data tend to perform well in code-oriented tasks. However, large-scale pretraining is not always feasible due to its environmental impact and project-specific generalizability issues. In this work, first we fine-tune open-source Large language models (LLM) in parameter-efficient, quantized low-rank (QLoRA) fashion on consumer-grade hardware to improve review comment generation. Recent studies demonstrate the efficacy of augmenting semantic metadata information into prompts to boost performance in other code-related tasks. To explore this in code review activities, we also prompt proprietary, closed-source LLMs augmenting the input code patch with function call graphs and code summaries. Both of our strategies improve the review comment generation performance, with function call graph augmented few-shot prompting on the GPT-3.5 model surpassing the pretrained baseline by around 90% BLEU-4 score on the CodeReviewer dataset. Moreover, few-shot prompted Gemini-1.0 Pro, QLoRA fine-tuned Code Llama and Llama 3.1 models achieve competitive results (ranging from 25% to 83% performance improvement) on this task. An additional human evaluation study further validates our experimental findings, reflecting real-world developers' perceptions of LLM-generated code review comments based on relevant qualitative metrics.

[Arxiv](https://arxiv.org/abs/2411.10129)