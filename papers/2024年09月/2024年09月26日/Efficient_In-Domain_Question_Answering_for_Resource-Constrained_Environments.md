# 在资源有限的环境中，实现高效的领域内问答

发布时间：2024年09月26日

`RAG` `信息技术` `问答系统`

> Efficient In-Domain Question Answering for Resource-Constrained Environments

# 摘要

> RAG 通过整合外部知识到 LLM 中，提升了 QA 任务的准确性和相关性。然而，提示工程和资源效率仍是开发稳健 RAG 解决方案的瓶颈。近期研究表明，RAFT 在较小模型上的表现优于大型模型如 GPT-3.5。结合 RAFT 与 LoRA 等 PEFT 技术，不仅能减少微调需求，还能加速推理，同时保持 RAG 性能。这种计算高效的 CRAFT 特别适合资源受限、网络受限的环境中的知识密集型 QA 任务。

> Retrieval Augmented Generation (RAG) is a common method for integrating external knowledge into pretrained Large Language Models (LLMs) to enhance accuracy and relevancy in question answering (QA) tasks. However, prompt engineering and resource efficiency remain significant bottlenecks in developing optimal and robust RAG solutions for real-world QA applications. Recent studies have shown success in using fine tuning to address these problems; in particular, Retrieval Augmented Fine Tuning (RAFT) applied to smaller 7B models has demonstrated superior performance compared to RAG setups with much larger models such as GPT-3.5. The combination of RAFT with parameter-efficient fine tuning (PEFT) techniques, such as Low-Rank Adaptation (LoRA), promises an even more efficient solution, yet remains an unexplored area. In this work, we combine RAFT with LoRA to reduce fine tuning and storage requirements and gain faster inference times while maintaining comparable RAG performance. This results in a more compute-efficient RAFT, or CRAFT, which is particularly useful for knowledge-intensive QA tasks in resource-constrained environments where internet access may be restricted and hardware resources limited.

[Arxiv](https://arxiv.org/abs/2409.17648)