# 深度是否总是王道？在判别词典模型中，我们探讨用深度学习网络取代线性映射的可能性。

发布时间：2024年10月05日

`LLM理论` `语言学`

> Is deeper always better? Replacing linear mappings with deep learning networks in the Discriminative Lexicon Model

# 摘要

> 近期，深度学习在语言认知建模中的应用日益增多。本研究探讨深度学习能否帮助我们更深入地理解说话者面临的学习挑战，超越传统的线性方法。我们采用了区分性词汇模型（DLM），该模型通过数值形式与意义向量之间的映射来模拟语言的理解与生成。以往，这些映射多为线性（线性区分性学习，LDL），而本研究中我们将其替换为深度密集神经网络（深度区分性学习，DDL）。结果显示，DDL在处理英语和荷兰语的大规模多样化数据集时表现更佳，但在爱沙尼亚语和台湾普通话中则未必。对于具有伪形态结构的词汇（如“slender”），DDL在某些情况下优于LDL。在平均反应时间任务中，DDL的表现不及频率信息线性映射（FIL），但经过频率信息优化的DDL（频率信息深度学习，FIDDL）则显著超越FIL。此外，尽管线性映射能有效模拟增量词汇学习，深度映射在这方面则稍显不足。总体而言，线性和深度映射均为理解语言提供了宝贵的信息。

> Recently, deep learning models have increasingly been used in cognitive modelling of language. This study asks whether deep learning can help us to better understand the learning problem that needs to be solved by speakers, above and beyond linear methods. We utilise the Discriminative Lexicon Model (DLM, Baayen et al., 2019), which models comprehension and production with mappings between numeric form and meaning vectors. While so far, these mappings have been linear (Linear Discriminative Learning, LDL), in the present study we replace them with deep dense neural networks (Deep Discriminative Learning, DDL). We find that DDL affords more accurate mappings for large and diverse datasets from English and Dutch, but not necessarily for Estonian and Taiwan Mandarin. DDL outperforms LDL in particular for words with pseudo-morphological structure such as slend+er. Applied to average reaction times, we find that DDL is outperformed by frequency-informed linear mappings (FIL). However, DDL trained in a frequency-informed way ('frequency-informed' deep learning, FIDDL) substantially outperforms FIL. Finally, while linear mappings can very effectively be updated from trial-to-trial to model incremental lexical learning (Heitmeier et al., 2023), deep mappings cannot do so as effectively. At present, both linear and deep mappings are informative for understanding language.

[Arxiv](https://arxiv.org/abs/2410.04259)