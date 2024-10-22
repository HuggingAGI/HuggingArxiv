# 大型语言模型赋能拍卖中的个性化估值

发布时间：2024年10月21日

`LLM应用`

> Large Language Models Empower Personalized Valuation in Auction

# 摘要

> 拍卖作为基础经济机制，涉及商品或服务的估值和竞争性投标算法，旨在揭示真实市场价值。然而，现有研究多聚焦于投标算法，忽略了将个人投标者的独特偏好和物品语义信息融入估值的优势。我们的理论与实证分析表明，估值的不精确或噪声会显著影响参与者效用。为此，我们提出了个性化估值框架——\textbf{S}emantic-enhanced \textbf{P}ersonalized \textbf{V}aluation in \textbf{A}uction (\ours)，结合大型语言模型 (LLMs) 将语义信息融入每个投标者的估值过程。SPVA 采用两阶段方法：首先微调 LLMs 以编码投标者偏好，然后在 Vickrey 拍卖环境中集成投标算法，证明更准确估值带来更高利润。此外，我们构建了包含 23,000 多个样本的语义增强数据集，并引入新的个性化评估指标，反映投标者偏好和利润。通过模拟多种拍卖场景，我们的方法展示了其提供准确估值和捕捉投标者偏好的能力，证实了其在现实拍卖环境中的有效性。

> Auctions, a fundamental economic mechanism, encompass the valuation of goods or services and the competitive bidding algorithms within a specific framework, serving to uncover the true market value. However, current research predominantly focuses on the bidding algorithms within a given auction mechanism, often overlooking the advantages of incorporating individual bidders' unique preferences and the semantic information related to the items into the valuation process. Our analysis, both theoretical and empirical, shows that imprecise or noisy valuations can significantly affect the overall utility for participants. To bridge this gap, we propose a personalized valuation framework, namely \textbf{S}emantic-enhanced \textbf{P}ersonalized \textbf{V}aluation in \textbf{A}uction (\ours), which integrates Large Language Models (LLMs) to incorporate semantic information into each bidder's unique valuation process. Specifically, SPVA employs a two-stage approach: it first fine-tunes LLMs to encode bidder preferences in personalized valuations, and then constructs a Vickrey auction environment integrated with a bidding algorithm to demonstrate that SPVA's more accurate valuations result in higher profits. Additionally, we have developed a semantic-enhanced dataset comprising over 23,000 samples and introduced new personalized evaluation metrics that reflect both bidder preferences and profit. Through simulations of various auction scenarios, our method demonstrates its ability to provide accurate valuations and capture bidder preferences, affirming the method's effectiveness in real-world auction settings.

[Arxiv](https://arxiv.org/abs/2410.15817)