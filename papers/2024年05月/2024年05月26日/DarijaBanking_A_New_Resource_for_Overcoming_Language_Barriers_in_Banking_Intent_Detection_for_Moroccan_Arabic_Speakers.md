# DarijaBanking：打破语言壁垒，助力摩洛哥阿拉伯语用户在银行意图检测中的新资源

发布时间：2024年05月26日

`LLM应用

这篇论文主要讨论了针对摩洛哥方言（Darija）在银行业中的应用，特别是通过创建一个名为 **DarijaBanking** 的数据集来提升意图分类能力。论文中提到的技术包括模型微调、零样本学习、检索方法和大型语言模型提示，并介绍了专为 Darija 设计的 BERT 语言模型（BERTouch）。这些内容主要关注于特定语言模型在实际应用中的表现和优化，因此属于LLM应用分类。` `银行业`

> DarijaBanking: A New Resource for Overcoming Language Barriers in Banking Intent Detection for Moroccan Arabic Speakers

# 摘要

> 在开发适应语言多样性的自然语言处理系统，尤其是在银行业等专业领域时，我们面临着重大挑战。摩洛哥方言（Darija）融合了文化、历史和地域的复杂性，为语言模型带来了独特挑战，因其与现代标准阿拉伯语不同，且深受法语、西班牙语和塔马齐格特语的影响，需要针对性的沟通策略。为此，我们推出了 **DarijaBanking** 数据集，专注于提升银行业中 Darija 的意图分类能力，满足摩洛哥客户母语交流的自动银行系统（如聊天机器人）的关键需求。该数据集包含超过 1,800 个高质量平行查询，涵盖 Darija、MSA、英语和法语，分为 24 个意图类别。我们探索了多种意图分类技术，包括模型微调、零样本学习、检索方法和大型语言模型提示。我们的主要成果之一是 BERTouch，一种专为 Darija 设计的 BERT 语言模型，其在 DarijaBanking 上的 F1 分数分别达到 0.98（Darija）和 0.96（MSA），超越了包括 GPT-4 在内的其他模型，证明了其在特定应用中的高效性。

> Navigating the complexities of language diversity is a central challenge in developing robust natural language processing systems, especially in specialized domains like banking. The Moroccan Dialect (Darija) serves as the common language that blends cultural complexities, historical impacts, and regional differences. The complexities of Darija present a special set of challenges for language models, as it differs from Modern Standard Arabic with strong influence from French, Spanish, and Tamazight, it requires a specific approach for effective communication. To tackle these challenges, this paper introduces \textbf{DarijaBanking}, a novel Darija dataset aimed at enhancing intent classification in the banking domain, addressing the critical need for automatic banking systems (e.g., chatbots) that communicate in the native language of Moroccan clients. DarijaBanking comprises over 1,800 parallel high-quality queries in Darija, Modern Standard Arabic (MSA), English, and French, organized into 24 intent classes. We experimented with various intent classification methods, including full fine-tuning of monolingual and multilingual models, zero-shot learning, retrieval-based approaches, and Large Language Model prompting. One of the main contributions of this work is BERTouch, our BERT-based language model for intent classification in Darija. BERTouch achieved F1-scores of 0.98 for Darija and 0.96 for MSA on DarijaBanking, outperforming the state-of-the-art alternatives including GPT-4 showcasing its effectiveness in the targeted application.

[Arxiv](https://arxiv.org/abs/2405.16482)