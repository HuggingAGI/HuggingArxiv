# 合成知识摄取：通过知识精炼与注入，提升大型语言模型的能力

发布时间：2024年10月12日

`LLM应用` `生物医学`

> Synthetic Knowledge Ingestion: Towards Knowledge Refinement and Injection for Enhancing Large Language Models

# 摘要

> 大型语言模型 (LLM) 在捕捉多领域事实知识方面表现出色，但在已知知识上精炼其能力或整合新知识仍面临挑战。为此，我们提出了一种名为 Ski 的新方法，通过细粒度合成、交错生成和组装增强策略，从原始知识源构建高质量数据表示。我们将 Ski 与三种知识注入技术（RAG、SFT 和 CPT）结合，以在语言模型中注入和精炼知识。实验结果显示，Ski 在金融、生物医学和开放生成领域的问答任务中，显著优于基线方法。我们相信，这项工作是提升 LLM 输出事实准确性的重要一步。

> Large language models (LLMs) are proficient in capturing factual knowledge across various domains. However, refining their capabilities on previously seen knowledge or integrating new knowledge from external sources remains a significant challenge. In this work, we propose a novel synthetic knowledge ingestion method called Ski, which leverages fine-grained synthesis, interleaved generation, and assemble augmentation strategies to construct high-quality data representations from raw knowledge sources. We then integrate Ski and its variations with three knowledge injection techniques: Retrieval Augmented Generation (RAG), Supervised Fine-tuning (SFT), and Continual Pre-training (CPT) to inject and refine knowledge in language models. Extensive empirical experiments are conducted on various question-answering tasks spanning finance, biomedicine, and open-generation domains to demonstrate that Ski significantly outperforms baseline methods by facilitating effective knowledge injection. We believe that our work is an important step towards enhancing the factual accuracy of LLM outputs by refining knowledge representation and injection capabilities.

[Arxiv](https://arxiv.org/abs/2410.09629)