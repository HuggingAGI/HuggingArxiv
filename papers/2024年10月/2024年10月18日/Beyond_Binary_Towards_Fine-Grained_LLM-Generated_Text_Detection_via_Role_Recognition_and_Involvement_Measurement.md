# 超越二元对立，通过角色识别与参与度测量，实现对 LLM 生成文本的精细检测。

发布时间：2024年10月18日

`LLM应用` `社交媒体` `信息安全`

> Beyond Binary: Towards Fine-Grained LLM-Generated Text Detection via Role Recognition and Involvement Measurement

# 摘要

> 随着ChatGPT等大型语言模型（LLMs）的迅猛发展，LLM生成内容在社交媒体上泛滥，引发了关于错误信息、数据偏见和隐私侵犯的担忧，威胁着在线对话的信任。尽管检测LLM生成内容至关重要，但现有方法多局限于简单的二元分类，难以应对人机协作等复杂场景。为此，我们提出了一种新的检测范式，引入了两个创新任务：LLM角色识别（LLM-RR）和LLM影响测量（LLM-IM），分别用于识别LLM在内容生成中的角色和量化其参与程度。我们设计的LLMDetect基准，包括混合新闻检测语料库（HNDC）和DetectEval评估套件，能够全面评估检测器在多样上下文中的表现。实验表明，微调的PLM模型在两个任务上表现优异，而先进的LLMs在自我检测方面仍面临挑战。这项研究不仅深化了对LLM生成内容的理解，也为更精细的检测方法奠定了基础。

> The rapid development of large language models (LLMs), like ChatGPT, has resulted in the widespread presence of LLM-generated content on social media platforms, raising concerns about misinformation, data biases, and privacy violations, which can undermine trust in online discourse. While detecting LLM-generated content is crucial for mitigating these risks, current methods often focus on binary classification, failing to address the complexities of real-world scenarios like human-AI collaboration. To move beyond binary classification and address these challenges, we propose a new paradigm for detecting LLM-generated content. This approach introduces two novel tasks: LLM Role Recognition (LLM-RR), a multi-class classification task that identifies specific roles of LLM in content generation, and LLM Influence Measurement (LLM-IM), a regression task that quantifies the extent of LLM involvement in content creation. To support these tasks, we propose LLMDetect, a benchmark designed to evaluate detectors' performance on these new tasks. LLMDetect includes the Hybrid News Detection Corpus (HNDC) for training detectors, as well as DetectEval, a comprehensive evaluation suite that considers five distinct cross-context variations and multi-intensity variations within the same LLM role. This allows for a thorough assessment of detectors' generalization and robustness across diverse contexts. Our empirical validation of 10 baseline detection methods demonstrates that fine-tuned PLM-based models consistently outperform others on both tasks, while advanced LLMs face challenges in accurately detecting their own generated content. Our experimental results and analysis offer insights for developing more effective detection models for LLM-generated content. This research enhances the understanding of LLM-generated content and establishes a foundation for more nuanced detection methodologies.

[Arxiv](https://arxiv.org/abs/2410.14259)