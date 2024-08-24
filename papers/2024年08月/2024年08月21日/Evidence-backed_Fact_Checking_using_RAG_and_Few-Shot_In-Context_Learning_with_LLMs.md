# 利用 RAG 和 LLM 进行少量样本上下文学习，实现基于证据的事实核查

发布时间：2024年08月21日

`RAG` `社交媒体` `信息安全`

> Evidence-backed Fact Checking using RAG and Few-Shot In-Context Learning with LLMs

# 摘要

> 社交媒体上的错误信息泛滥，使得在线声明的事实核查变得至关重要。手动验证每条声明极为困难，因此我们设计了一个自动化系统来应对这一挑战。该系统利用 Averitec 数据集评估声明的真实性，并提供支持证据。通过 Retrieve and Generate (RAG) 流程，我们从知识库中提取相关证据，结合声明输入 LLM 进行分类。此外，我们还评估了 LLM 的少量样本 In-Context Learning (ICL) 能力。我们的系统在 'Averitec' 评分上比基线提升了 22%，所有代码将在 GitHub 上公开。

> Given the widespread dissemination of misinformation on social media, implementing fact-checking mechanisms for online claims is essential. Manually verifying every claim is highly challenging, underscoring the need for an automated fact-checking system. This paper presents our system designed to address this issue. We utilize the Averitec dataset to assess the veracity of claims. In addition to veracity prediction, our system provides supporting evidence, which is extracted from the dataset. We develop a Retrieve and Generate (RAG) pipeline to extract relevant evidence sentences from a knowledge base, which are then inputted along with the claim into a large language model (LLM) for classification. We also evaluate the few-shot In-Context Learning (ICL) capabilities of multiple LLMs. Our system achieves an 'Averitec' score of 0.33, which is a 22% absolute improvement over the baseline. All code will be made available on All code will be made available on https://github.com/ronit-singhal/evidence-backed-fact-checking-using-rag-and-few-shot-in-context-learning-with-llms.

[Arxiv](https://arxiv.org/abs/2408.12060)