# $statcheck$ 设计上有缺陷，无法作为有效的统计结果拼写检查工具。

发布时间：2024年08月15日

`LLM应用` `科学研究` `统计学`

> $statcheck$ is flawed by design and no valid spell checker for statistical results

# 摘要

> R包$statcheck$主要用于从文本中提取并验证统计测试结果的一致性，近期还被用作统计结果的拼写检查工具，以提升科学文献的准确性。本研究通过187个包含各种统计结果的文本字符串测试了$statcheck$的性能。这些字符串涵盖了正确结果、非目标统计量、多样报告风格及常见错误等多种情况。由于$statcheck$的检测算法仅适用于严格遵循APA指南的统计结果，对于稍有偏离的报告则无法识别。因此，$statcheck$在实际应用中难以有效检测文献中的统计结果。结论是，$statcheck$的功能和实用性有限，不宜用于检测结果异常或作为统计结果的拼写检查工具。未来改进应考虑采用更灵活的算法，如$JATSdecoder$和大型语言模型所展示的，以适应更多样的报告风格，但这些技术仍无法替代专业读者的审慎判断。

> The R package $statcheck$ is designed to extract statistical test results from text and check the consistency of the reported test statistics and corresponding p-values. Recently, it has also been featured as a spell checker for statistical results, aimed at improving reporting accuracy in scientific publications. In this study, I perform a check on $statcheck$ using a non-exhaustive list of 187 simple text strings with arbitrary statistical test results. These strings represent a wide range of textual representations of results including correctly manageable results, non-targeted test statistics, variable reporting styles, and common typos. Since $statcheck$'s detection heuristic is tied to a specific set of statistical test results that strictly adhere to the American Psychological Association (APA) reporting guidelines, it is unable to detect and check any reported result that even slightly deviates from this narrow style. In practice, $statcheck$ is unlikely to detect many statistical test results reported in the literature. I conclude that the capabilities and usefulness of the $statcheck$ software are very limited and that it should not be used to detect irregularities in results nor as a spell checker for statistical results. Future developments should aim to incorporate more flexible algorithms capable of handling a broader variety of reporting styles, such as those provided by $JATSdecoder$ and Large Language Models, which show promise in overcoming these limitations but they cannot replace the critical eye of a knowledgeable reader.

[Arxiv](https://arxiv.org/abs/2408.07948)