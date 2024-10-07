# Auto-GDA：自动域适应，助力检索增强生成中的高效基础验证

发布时间：2024年10月04日

`RAG` `人工智能`

> Auto-GDA: Automatic Domain Adaptation for Efficient Grounding Verification in Retrieval Augmented Generation

# 摘要

> 尽管 RAG 能提升 LLM 输出的事实准确性，但 LLM 仍会生成错误信息。常见检测方法需再次提示 LLM，成本高昂。轻量级 NLI 模型虽有潜力，但在复杂 RAG 输入上表现不佳。RAG 输入复杂，需特定领域适应，但缺乏标记数据。为此，我们提出 Auto-GDA，通过合成数据实现无监督适应。与手工策略不同，Auto-GDA 利用迭代优化，持续提升样本质量。实验显示，Auto-GDA 微调模型性能超越教师模型，且计算成本仅为 LLM 的 10%。

> While retrieval augmented generation (RAG) has been shown to enhance factuality of large language model (LLM) outputs, LLMs still suffer from hallucination, generating incorrect or irrelevant information. One common detection strategy involves prompting the LLM again to assess whether its response is grounded in the retrieved evidence, but this approach is costly. Alternatively, lightweight natural language inference (NLI) models for efficient grounding verification can be used at inference time. While existing pre-trained NLI models offer potential solutions, their performance remains subpar compared to larger models on realistic RAG inputs. RAG inputs are more complex than most datasets used for training NLI models and have characteristics specific to the underlying knowledge base, requiring adaptation of the NLI models to a specific target domain. Additionally, the lack of labeled instances in the target domain makes supervised domain adaptation, e.g., through fine-tuning, infeasible. To address these challenges, we introduce Automatic Generative Domain Adaptation (Auto-GDA). Our framework enables unsupervised domain adaptation through synthetic data generation. Unlike previous methods that rely on handcrafted filtering and augmentation strategies, Auto-GDA employs an iterative process to continuously improve the quality of generated samples using weak labels from less efficient teacher models and discrete optimization to select the most promising augmented samples. Experimental results demonstrate the effectiveness of our approach, with models fine-tuned on synthetic data using Auto-GDA often surpassing the performance of the teacher model and reaching the performance level of LLMs at 10 % of their computational cost.

[Arxiv](https://arxiv.org/abs/2410.03461)