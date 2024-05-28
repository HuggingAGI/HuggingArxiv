# DarijaBanking：助力摩洛哥阿拉伯语用户跨越银行意图检测的语言鸿沟的新工具

发布时间：2024年05月26日

`LLM应用

理由：这篇论文主要关注于特定语言（摩洛哥方言Darija）在特定领域（银行）的应用，通过开发和评估一个专门的数据集（DarijaBanking）以及相应的模型（BERTouch）来解决语言多样性和专业领域的需求。这表明论文的重点是在实际应用中使用大型语言模型（LLM）来解决具体问题，而不是探讨LLM的理论基础或Agent的设计，也不是关于检索增强生成（RAG）的研究。因此，将其归类为LLM应用是合适的。`

> DarijaBanking: A New Resource for Overcoming Language Barriers in Banking Intent Detection for Moroccan Arabic Speakers

# 摘要

> 在开发强大的自然语言处理系统时，应对语言多样性的复杂性是一项核心挑战，特别是在银行等专业领域。摩洛哥方言（Darija）融合了文化、历史和地区的多样性，为语言模型带来了独特的挑战，因其与现代标准阿拉伯语不同，深受法语、西班牙语和塔马齐格特语的影响。为此，我们推出了DarijaBanking数据集，旨在提升银行领域的意图分类，满足自动银行系统（如聊天机器人）以摩洛哥客户母语沟通的需求。该数据集包含超过1,800个高质量平行查询，涵盖Darija、MSA、英语和法语，分为24个意图类别。我们尝试了多种意图分类技术，包括模型微调、零样本学习等。我们的BERTouch模型在DarijaBanking上取得了优异成绩，Darija和MSA的F1分数分别达到0.98和0.96，超越了包括GPT-4在内的现有技术，证明了其在特定应用中的高效性。

> Navigating the complexities of language diversity is a central challenge in developing robust natural language processing systems, especially in specialized domains like banking. The Moroccan Dialect (Darija) serves as the common language that blends cultural complexities, historical impacts, and regional differences. The complexities of Darija present a special set of challenges for language models, as it differs from Modern Standard Arabic with strong influence from French, Spanish, and Tamazight, it requires a specific approach for effective communication. To tackle these challenges, this paper introduces \textbf{DarijaBanking}, a novel Darija dataset aimed at enhancing intent classification in the banking domain, addressing the critical need for automatic banking systems (e.g., chatbots) that communicate in the native language of Moroccan clients. DarijaBanking comprises over 1,800 parallel high-quality queries in Darija, Modern Standard Arabic (MSA), English, and French, organized into 24 intent classes. We experimented with various intent classification methods, including full fine-tuning of monolingual and multilingual models, zero-shot learning, retrieval-based approaches, and Large Language Model prompting. One of the main contributions of this work is BERTouch, our BERT-based language model for intent classification in Darija. BERTouch achieved F1-scores of 0.98 for Darija and 0.96 for MSA on DarijaBanking, outperforming the state-of-the-art alternatives including GPT-4 showcasing its effectiveness in the targeted application.

[Arxiv](https://arxiv.org/abs/2405.16482)