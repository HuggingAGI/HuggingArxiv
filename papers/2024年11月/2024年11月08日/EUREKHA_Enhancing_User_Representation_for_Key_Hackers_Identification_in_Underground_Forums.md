# EUREKHA：增强用于地下论坛中关键黑客识别的用户表示

发布时间：2024年11月08日

`LLM应用` `网络安全` `地下论坛`

> EUREKHA: Enhancing User Representation for Key Hackers Identification in Underground Forums

# 摘要

> 地下论坛是网络犯罪活动的中心，为匿名和逃避常规在线监督提供了空间。在这些隐藏的社区中，恶意行为者合作交流非法知识、工具和策略，推动了从黑客技术到被盗数据、恶意软件和零日漏洞利用的销售等一系列网络威胁。确定这些操作背后的关键煽动者（即关键黑客）至关重要，但仍然是一个复杂的挑战。本文提出了一种称为 EUREKHA（增强地下论坛中关键黑客识别的用户表示）的新方法，旨在通过将每个用户建模为文本序列来识别这些关键黑客。此序列通过大型语言模型（LLM）进行特定领域的适应，LLM 充当特征提取器。然后将这些提取的特征输入到图神经网络（GNN）中以对用户结构关系进行建模，显著提高识别准确性。此外，我们采用 BERTopic（来自 Transformer 的双向编码器表示主题建模）从用户生成的内容中提取个性化主题，为每个用户实现多个文本表示，并优化最具代表性序列的选择。我们的研究表明，微调的 LLM 在识别关键黑客方面优于最先进的方法。此外，当与 GNN 结合时，我们的模型实现了显著的改进，与现有方法相比，准确率和 F1 分数分别提高了约 6％和 10％。EUREKHA 在 Hack-Forums 数据集上进行了测试，我们提供了代码的开源访问。

> Underground forums serve as hubs for cybercriminal activities, offering a space for anonymity and evasion of conventional online oversight. In these hidden communities, malicious actors collaborate to exchange illicit knowledge, tools, and tactics, driving a range of cyber threats from hacking techniques to the sale of stolen data, malware, and zero-day exploits. Identifying the key instigators (i.e., key hackers), behind these operations is essential but remains a complex challenge. This paper presents a novel method called EUREKHA (Enhancing User Representation for Key Hacker Identification in Underground Forums), designed to identify these key hackers by modeling each user as a textual sequence. This sequence is processed through a large language model (LLM) for domain-specific adaptation, with LLMs acting as feature extractors. These extracted features are then fed into a Graph Neural Network (GNN) to model user structural relationships, significantly improving identification accuracy. Furthermore, we employ BERTopic (Bidirectional Encoder Representations from Transformers Topic Modeling) to extract personalized topics from user-generated content, enabling multiple textual representations per user and optimizing the selection of the most representative sequence. Our study demonstrates that fine-tuned LLMs outperform state-of-the-art methods in identifying key hackers. Additionally, when combined with GNNs, our model achieves significant improvements, resulting in approximately 6% and 10% increases in accuracy and F1-score, respectively, over existing methods. EUREKHA was tested on the Hack-Forums dataset, and we provide open-source access to our code.

[Arxiv](https://arxiv.org/abs/2411.05479)