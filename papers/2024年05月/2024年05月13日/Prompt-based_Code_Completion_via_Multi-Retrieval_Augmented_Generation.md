# 基于提示的多重检索增强生成实现代码补全

发布时间：2024年05月13日

`RAG

这篇论文介绍了一个名为ProCC的框架，它通过提示工程和上下文多臂老虎机算法来改进自动代码补全技术。ProCC框架特别关注于通过多检索器系统和自适应检索选择算法来融合多种代码视角，以提高检索增强生成（RAG）技术的性能。这与RAG分类相关，因为它专注于通过检索增强生成技术来改善大型语言模型（LLM）在代码补全任务中的应用。虽然它也涉及LLM的应用，但主要焦点是RAG技术的改进，因此更适合归类为RAG。` `软件开发` `人工智能辅助编程`

> Prompt-based Code Completion via Multi-Retrieval Augmented Generation

# 摘要

> 自动代码补全技术得益于预训练大型语言模型（LLMs）的进步，但在处理复杂代码逻辑或超出训练数据范围时，常面临连贯性和幻觉问题。现有的检索增强生成（RAG）技术虽有所改善，但其检索视角单一，未能充分考虑代码语义的复杂多变。为此，我们推出了ProCC框架，它通过提示工程和上下文多臂老虎机算法，灵活融合多种代码视角。ProCC首先通过多检索器系统，利用提示模板激发LLM理解代码语义的多重视角。接着，采用自适应检索选择算法，结合代码相似性，为LLM选择最佳的补全视角。实验证明，ProCC在开源和私有领域基准测试中分别超越现有技术8.6%和10.1%，在精确匹配方面表现卓越。此外，ProCC还能无缝集成微调技术，提升性能达5.6%。

> Automated code completion, aiming at generating subsequent tokens from unfinished code, has been significantly benefited from recent progress in pre-trained Large Language Models (LLMs). However, these models often suffer from coherence issues and hallucinations when dealing with complex code logic or extrapolating beyond their training data. Existing Retrieval Augmented Generation (RAG) techniques partially address these issues by retrieving relevant code with a separate encoding model where the retrieved snippet serves as contextual reference for code completion. However, their retrieval scope is subject to a singular perspective defined by the encoding model, which largely overlooks the complexity and diversity inherent in code semantics. To address this limitation, we propose ProCC, a code completion framework leveraging prompt engineering and the contextual multi-armed bandits algorithm to flexibly incorporate and adapt to multiple perspectives of code. ProCC first employs a prompt-based multi-retriever system which crafts prompt templates to elicit LLM knowledge to understand code semantics with multiple retrieval perspectives. Then, it adopts the adaptive retrieval selection algorithm to incorporate code similarity into the decision-making process to determine the most suitable retrieval perspective for the LLM to complete the code. Experimental results demonstrate that ProCC outperforms state-of-the-art code completion technique by 8.6% on our collected open-source benchmark suite and 10.1% on the private-domain benchmark suite collected from a billion-user e-commerce company in terms of Exact Match. ProCC also allows augmenting fine-tuned techniques in a plug-and-play manner, yielding 5.6% improvement over our studied fine-tuned model.

[Arxiv](https://arxiv.org/abs/2405.07530)