# ESPERANTO：通过评估合成短语，提升 AI 检测文本来源的鲁棒性

发布时间：2024年09月21日

`LLM应用` `网络安全` `人工智能`

> ESPERANTO: Evaluating Synthesized Phrases to Enhance Robustness in AI Detection for Text Origination

# 摘要

> 尽管大型语言模型 (LLM) 在多个领域表现出色，但也容易被用于不道德行为，如学术欺诈和错误信息传播。因此，AI 文本检测系统应运而生，但这些系统对规避技巧和文本操作的抵抗力不足。本文提出回译作为一种新的规避技术，强调了提升当前检测系统鲁棒性的重要性。我们通过多语言翻译和回译，生成一个经过操纵的 AI 文本版本，保留原始语义的同时显著降低现有检测方法的准确率。我们在九个检测器上测试了这一技术，发现它们对回译操纵的脆弱性。为此，我们提出了一种增强鲁棒性的反制措施，结果显示，回译后检测准确率仅下降了 1.85%。此外，我们创建了一个包含 72 万文本的大型数据集，涵盖多种领域和写作风格，以评估我们的方法和现有检测器的性能，并公开分享该数据集，以促进研究。

> While large language models (LLMs) exhibit significant utility across various domains, they simultaneously are susceptible to exploitation for unethical purposes, including academic misconduct and dissemination of misinformation. Consequently, AI-generated text detection systems have emerged as a countermeasure. However, these detection mechanisms demonstrate vulnerability to evasion techniques and lack robustness against textual manipulations. This paper introduces back-translation as a novel technique for evading detection, underscoring the need to enhance the robustness of current detection systems. The proposed method involves translating AI-generated text through multiple languages before back-translating to English. We present a model that combines these back-translated texts to produce a manipulated version of the original AI-generated text. Our findings demonstrate that the manipulated text retains the original semantics while significantly reducing the true positive rate (TPR) of existing detection methods. We evaluate this technique on nine AI detectors, including six open-source and three proprietary systems, revealing their susceptibility to back-translation manipulation. In response to the identified shortcomings of existing AI text detectors, we present a countermeasure to improve the robustness against this form of manipulation. Our results indicate that the TPR of the proposed method declines by only 1.85% after back-translation manipulation. Furthermore, we build a large dataset of 720k texts using eight different LLMs. Our dataset contains both human-authored and LLM-generated texts in various domains and writing styles to assess the performance of our method and existing detectors. This dataset is publicly shared for the benefit of the research community.

[Arxiv](https://arxiv.org/abs/2409.14285)