# 揭秘大型语言模型生成的文本：多层次细粒度检测框架

发布时间：2024年10月18日

`LLM应用`

> Unveiling Large Language Models Generated Texts: A Multi-Level Fine-Grained Detection Framework

# 摘要

> 大型语言模型（LLM）通过提升语法、内容和风格，彻底改变了写作。然而，其广泛应用引发了关于作者身份、原创性和伦理的担忧，甚至可能威胁学术诚信。现有检测方法多依赖单一特征分析和二元分类，难以有效识别学术背景下的LLM生成文本。为此，我们提出了多层次细粒度检测（MFD）框架，整合低层次结构、高层次语义和深层次语言特征，并进行句子级别的词汇、语法和句法评估，实现全面分析。为提高对细微差异的检测能力并增强对改写攻击的鲁棒性，我们应用两种主流规避技术重写文本，并通过对比学习训练文本编码器，提取高层次语义特征，增强检测泛化能力。此外，我们利用先进LLM分析整个文本，提取深层次语言特征，增强模型捕捉复杂模式和细微差别的能力，有效整合上下文信息。实验表明，MFD模型在公共数据集上表现优异，MAE为0.1346，准确率达88.56%。该研究为机构和出版商提供了一种有效机制，用于检测LLM生成文本，减轻作者身份受损风险。教育者和编辑可利用模型预测结果，改进验证和抄袭预防协议，确保持续遵守标准。

> Large language models (LLMs) have transformed human writing by enhancing grammar correction, content expansion, and stylistic refinement. However, their widespread use raises concerns about authorship, originality, and ethics, even potentially threatening scholarly integrity. Existing detection methods, which mainly rely on single-feature analysis and binary classification, often fail to effectively identify LLM-generated text in academic contexts. To address these challenges, we propose a novel Multi-level Fine-grained Detection (MFD) framework that detects LLM-generated text by integrating low-level structural, high-level semantic, and deep-level linguistic features, while conducting sentence-level evaluations of lexicon, grammar, and syntax for comprehensive analysis. To improve detection of subtle differences in LLM-generated text and enhance robustness against paraphrasing, we apply two mainstream evasion techniques to rewrite the text. These variations, along with original texts, are used to train a text encoder via contrastive learning, extracting high-level semantic features of sentence to boost detection generalization. Furthermore, we leverage advanced LLM to analyze the entire text and extract deep-level linguistic features, enhancing the model's ability to capture complex patterns and nuances while effectively incorporating contextual information. Extensive experiments on public datasets show that the MFD model outperforms existing methods, achieving an MAE of 0.1346 and an accuracy of 88.56%. Our research provides institutions and publishers with an effective mechanism to detect LLM-generated text, mitigating risks of compromised authorship. Educators and editors can use the model's predictions to refine verification and plagiarism prevention protocols, ensuring adherence to standards.

[Arxiv](https://arxiv.org/abs/2410.14231)