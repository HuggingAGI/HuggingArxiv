# 通过投注进行的顺序假设检验来在线检测 LLM 生成的文本

发布时间：2024年10月29日

`LLM应用` `检测算法`

> Online Detecting LLM-Generated Texts via Sequential Hypothesis Testing by Betting

# 摘要

> 近年来，开发能区分机器生成文本和人类编写文本的算法备受关注。当前此方向的现有方法通常处于离线状态，即预先给定一个包含真实文本和机器生成文本的混合数据集，任务是判断数据集中的每个样本是出自大型语言模型（LLM）还是人类。然而，在诸多实际场景中，像新闻网站、社交媒体账号或其他论坛之类的来源是以流式发布内容的。所以，在这种在线场景下，如何迅速且精准地判定来源是否为具有可靠统计保证的LLM，对于这些媒体或平台的有效运行以及防止错误信息传播和LLM的其他潜在滥用至关重要。为解决在线检测的难题，我们基于序贯假设检验技术开发了一种算法，通过打赌的方式，不仅依托并补充了现有的离线检测技术，还具备统计保障，包括可控的假阳性率以及正确识别来源为LLM的预期时间。我们开展了实验以证明该方法的有效性。

> Developing algorithms to differentiate between machine-generated texts and human-written texts has garnered substantial attention in recent years. Existing methods in this direction typically concern an offline setting where a dataset containing a mix of real and machine-generated texts is given upfront, and the task is to determine whether each sample in the dataset is from a large language model (LLM) or a human. However, in many practical scenarios, sources such as news websites, social media accounts, or on other forums publish content in a streaming fashion. Therefore, in this online scenario, how to quickly and accurately determine whether the source is an LLM with strong statistical guarantees is crucial for these media or platforms to function effectively and prevent the spread of misinformation and other potential misuse of LLMs. To tackle the problem of online detection, we develop an algorithm based on the techniques of sequential hypothesis testing by betting that not only builds upon and complements existing offline detection techniques but also enjoys statistical guarantees, which include a controlled false positive rate and the expected time to correctly identify a source as an LLM. Experiments were conducted to demonstrate the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2410.22318)