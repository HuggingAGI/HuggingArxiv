# 可解释性检测器：探究基于Transformer的语言模型在短信垃圾邮件检测中的应用，并结合可解释性分析，以揭示模型决策的内在机制。
发布时间：2024年05月12日

`文本分类`
> ExplainableDetector: Exploring Transformer-based Language Modeling Approach for SMS Spam Detection with Explainability Analysis
>
> 短消息服务（SMS）曾是一种便捷且经济的沟通方式，如今却沦为垃圾短信的温床。随着智能手机的普及和互联网的连接，垃圾短信已成为普遍的威胁。垃圾邮件发送者看中了SMS在移动通信中的重要性，导致垃圾短信数量激增。SMS数据的无序性给垃圾短信检测带来了挑战，使得在网络安全领域有效打击垃圾短信攻击变得更为复杂。本研究采用经过优化和微调的基于变压器的巨型语言模型（LLMs）来应对这一挑战。我们利用一个标准的SMS垃圾邮件数据集，并通过预处理技术净化数据，同时采用文本增强技术解决类别不平衡问题。实验结果显示，我们微调的BERT变体模型RoBERTa达到了99.84%的高准确率。我们还运用可解释人工智能（XAI）技术，通过正负系数分数揭示模型在文本垃圾短信检测中的透明度。同时，我们对比了传统机器学习模型与基于变压器的模型的性能，展示了LLMs在处理网络安全领域复杂文本垃圾邮件数据方面的潜力。
>
> https://arxiv.org/abs/2405.08026

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/Methodology.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/Dataset.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/ImBalanced.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/Balanced.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/Fine-Tuning.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/Explainability.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/Imbalanced_loss_and_accuracy.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/accuracy_imbalanced.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/Balanced_loss_and_accuracy.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/accuracy_balanced.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/Text-1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/LIME-Explanation-Text-First.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/Text-2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/LIME-Explanation-Text-Second.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/Text-3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/LIME-Explanation-Text-Third.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/Text-4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/LIME-Explanation-Text-Fourth.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/interpret-1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/interpret-2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/interpret-3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.08026/interpret-4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.08026](https://arxiv.org/abs/2405.08026)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886