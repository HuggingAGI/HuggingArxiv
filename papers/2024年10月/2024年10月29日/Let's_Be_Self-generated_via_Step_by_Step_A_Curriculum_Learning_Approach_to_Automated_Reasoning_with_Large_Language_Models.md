# 让我们逐步实现自我生成：大型语言模型自动推理的一种课程学习方式

发布时间：2024年10月29日

`LLM应用` `语言模型`

> Let's Be Self-generated via Step by Step: A Curriculum Learning Approach to Automated Reasoning with Large Language Models

# 摘要

> 尽管思维链（CoT）提示方式显著增强了大型语言模型（LLMs）的推理能力，然而它们仍存在一些局限性，要么需要耗费大量人力，要么性能有待提升。现有的尝试都致力于填补这些空缺；但这些方法要么依赖外部数据且无法彻底免除人工操作，要么难以有效引导 LLMs 生成高质量的示例提示。为应对上述不足，我们受课程学习启发，提出了一种名为	extbf{LBS3}的新型自动推理提示方法，它更贴合人类的学习习惯。具体而言，LBS3 起初引导 LLMs 回忆与目标查询相关的从易到难的代理查询。接着，它采用一种渐进策略，利用源自易代理查询的示例提示来指引 LLMs 解决难代理查询，以实现代理解决方案的高品质。最后，我们针对不同的开源和闭源 LLMs 在各类推理密集型任务中开展了大量实验，结果显示 LBS3 相较于 SOTA 基线取得了极具竞争力的表现。

> While Chain of Thought (CoT) prompting approaches have significantly consolidated the reasoning capabilities of large language models (LLMs), they still face limitations that require extensive human effort or have performance needs to be improved. Existing endeavors have focused on bridging these gaps; however, these approaches either hinge on external data and cannot completely eliminate manual effort, or they fall short in effectively directing LLMs to generate high-quality exemplary prompts. To address the said pitfalls, we propose a novel prompt approach for automatic reasoning named \textbf{LBS3}, inspired by curriculum learning which better reflects human learning habits. Specifically, LBS3 initially steers LLMs to recall easy-to-hard proxy queries that are pertinent to the target query. Following this, it invokes a progressive strategy that utilizes exemplary prompts stemmed from easy-proxy queries to direct LLMs in solving hard-proxy queries, enabling the high-quality of the proxy solutions. Finally, our extensive experiments in various reasoning-intensive tasks with varying open- and closed-source LLMs show that LBS3 achieves strongly competitive performance compared to the SOTA baselines.

[Arxiv](https://arxiv.org/abs/2410.21728)