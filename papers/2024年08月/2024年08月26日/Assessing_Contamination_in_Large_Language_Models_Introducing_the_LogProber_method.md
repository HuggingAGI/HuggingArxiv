# 探索大型语言模型中的污染问题，我们引入了 LogProber 方法，旨在更精准地评估和解决这一挑战。

发布时间：2024年08月26日

`LLM应用` `机器学习` `心理学`

> Assessing Contamination in Large Language Models: Introducing the LogProber method

# 摘要

> 在机器学习领域，污染问题不容忽视，它涉及测试数据意外渗入训练集。尤其在评估大型语言模型（LLM）性能时，这一问题更显突出，因为这些模型常基于从互联网上抓取的庞大而晦涩的文本数据进行训练。为此，开发能够检测污染的工具，对于公正且准确地监测LLM性能的进步至关重要。然而，当前多数研究并未专门针对心理学问卷等短文本序列的污染量化进行优化。本文中，我们推出了LogProber算法，它以高效著称，能通过分析句子中的标记概率来识别污染。随后，我们深入探讨了该算法的局限性，并揭示了某些训练方法如何在不留痕迹的情况下对模型造成污染。

> In machine learning, contamination refers to situations where testing data leak into the training set. The issue is particularly relevant for the evaluation of the performance of Large Language Models (LLMs), which are generally trained on gargantuan, and generally opaque, corpora of text scraped from the world wide web. Developing tools to detect contamination is therefore crucial to be able to fairly and properly track the evolution of the performance of LLMs. Most recent works in the field are not tailored to quantify contamination on short sequences of text like we find in psychology questionnaires. In the present paper we introduce LogProber, a novel, efficient, algorithm that we show able to detect contamination using token probability in given sentences. In the second part we investigate the limitations of the method and discuss how different training methods can contaminate models without leaving traces in the token probabilities.

[Arxiv](https://arxiv.org/abs/2408.14352)