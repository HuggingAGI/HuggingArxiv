# PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击

发布时间：2024年02月12日

`RAG

这篇论文主要关注的是检索增强生成（RAG）技术中的安全性问题，特别是提出了一种名为PoisonedRAG的知识中毒攻击方法。这种攻击方法允许攻击者在RAG系统的知识库中植入恶意文本，从而影响LLM的输出。论文详细描述了这种攻击的模型和实现方式，并进行了实验验证其有效性。因此，这篇论文的主题与RAG技术的应用和安全性紧密相关，属于RAG分类。` `信息安全` `人工智能`

> PoisonedRAG: Knowledge Poisoning Attacks to Retrieval-Augmented Generation of Large Language Models

# 摘要

> 大型语言模型（LLMs）凭借其卓越的生成能力取得了显著成就。然而，它们也面临固有限制，如知识陈旧和幻觉问题。检索增强生成（RAG）作为尖端技术，旨在克服这些挑战。当面对问题时，RAG 从庞大的知识库中提取相关信息，以丰富 LLM 的输入。例如，若知识库包含数百万维基百科文章，RAG 将找出与问题语义最相近的前 k 篇文章。借助这些信息，LLM 能够基于检索到的上下文生成答案。尽管 RAG 在提升准确性和效率方面已有研究，但其安全性问题却鲜为人关注。本研究致力于填补这一空白，提出 PoisonedRAG，一种针对 RAG 的知识中毒攻击，允许攻击者在知识库中植入少量恶意文本，诱导 LLM 为特定问题生成预设答案。我们将此类攻击建模为优化问题，并根据攻击者对 RAG 的了解程度（黑盒或白盒），提出两种解法。实验结果显示，在包含数百万文章的数据库中，每目标问题注入 5 篇中毒文本，攻击成功率高达 90%。我们还测试了现有防御措施，发现它们难以抵御此类攻击，强调了开发新防御策略的紧迫性。

> Large language models (LLMs) have achieved remarkable success due to their exceptional generative capabilities. Despite their success, they also have inherent limitations such as a lack of up-to-date knowledge and hallucination. Retrieval-Augmented Generation (RAG) is a state-of-the-art technique to mitigate those limitations. In particular, given a question, RAG retrieves relevant knowledge from a knowledge database to augment the input of the LLM. For instance, the retrieved knowledge could be a set of top-k texts that are most semantically similar to the given question when the knowledge database contains millions of texts collected from Wikipedia. As a result, the LLM could utilize the retrieved knowledge as the context to generate an answer for the given question. Existing studies mainly focus on improving the accuracy or efficiency of RAG, leaving its security largely unexplored. We aim to bridge the gap in this work. Particularly, we propose PoisonedRAG , a set of knowledge poisoning attacks to RAG, where an attacker could inject a few poisoned texts into the knowledge database such that the LLM generates an attacker-chosen target answer for an attacker-chosen target question. We formulate knowledge poisoning attacks as an optimization problem, whose solution is a set of poisoned texts. Depending on the background knowledge (e.g., black-box and white-box settings) of an attacker on the RAG, we propose two solutions to solve the optimization problem, respectively. Our results on multiple benchmark datasets and LLMs show our attacks could achieve 90% attack success rates when injecting 5 poisoned texts for each target question into a database with millions of texts. We also evaluate recent defenses and our results show they are insufficient to defend against our attacks, highlighting the need for new defenses.

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x1.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x2.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x3.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x4.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x5.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x6.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x7.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x8.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x9.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x10.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x11.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x12.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x13.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x14.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x15.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x16.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x17.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x18.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x19.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x20.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x21.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x22.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x23.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x24.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x25.png)

![PoisonedRAG：大型语言模型检索增强生成遭遇知识投毒攻击](../../../paper_images/2402.07867/x26.png)

[Arxiv](https://arxiv.org/abs/2402.07867)