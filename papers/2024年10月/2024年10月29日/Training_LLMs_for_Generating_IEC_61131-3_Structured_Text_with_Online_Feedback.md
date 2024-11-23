# 训练大型语言模型，利用在线反馈来生成 IEC 61131-3 结构化文本

发布时间：2024年10月29日

`LLM应用` `工业自动化` `代码生成`

> Training LLMs for Generating IEC 61131-3 Structured Text with Online Feedback

# 摘要

> 诸如 GPT-4 之类的大型语言模型（LLMs）的问世，在各领域的代码生成方面实现了重大突破。不过，由于公共训练数据集中数据有限以及 ST 语言语法复杂，这些模型在生成 IEC 61131-3 结构化文本（ST）代码时遭遇独特挑战。此文提出一种训练 LLMs 的新颖方法，着重通过包含编译器反馈和来自次级 LLM 评估的在线流程来提升学习数据的质量。在此框架中，主 LLM 生成新的训练样本，随后由编译器评估语法正确性，再由擅长评估语义准确性的专门 LLM 进行评估，尽管其本身并非为代码生成而优化。通过对训练数据的反复优化，该方法使训练后的 LLM 有显著提升，带来更高的编译成功率和更优的语义精度。故而，该框架在工业自动化应用中极为适用，且性能优于前沿模型。

> The advent of large language models (LLMs), such as GPT-4, has enabled significant advancements in generating code across various domains. However, these models face unique challenges when generating IEC 61131-3 Structured Text (ST) code due to limited data in public training datasets and the complexity of ST language syntax. This paper proposes a novel approach to training LLMs that emphasizes improving the quality of learning data through an online process involving compiler feedback and evaluation from a secondary LLM. In this framework, the primary LLM generates new training samples, which are subsequently evaluated by a compiler for syntactical correctness and by a specialized LLM that excels at assessing semantic accuracy, though it is not optimized for code generation itself. Through iterative refinement of the training data, this approach results in marked improvements for the trained LLM, leading to higher compilation success rates and better semantic precision. As a result, the framework proves highly suitable for industrial automation applications and outperforms state-of-the-art models.

[Arxiv](https://arxiv.org/abs/2410.22159)