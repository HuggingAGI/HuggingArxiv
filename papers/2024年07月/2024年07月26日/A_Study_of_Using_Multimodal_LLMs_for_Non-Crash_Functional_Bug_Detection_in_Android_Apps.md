# 本研究探索了利用多模态大型语言模型（LLM）检测安卓应用中的非崩溃功能性错误。

发布时间：2024年07月26日

`LLM应用` `软件测试` `移动应用`

> A Study of Using Multimodal LLMs for Non-Crash Functional Bug Detection in Android Apps

# 摘要

> 为了突破传统GUI测试方法在检测非崩溃功能错误上的局限，我们探索了大型语言模型（LLMs）作为安卓应用测试预言的新途径。基于LLMs丰富的移动应用使用和错误报告训练数据，我们相信它们能有效识别NCF错误。实证研究显示，LLMs在检测71个已知NCF错误中达到了49%的检测率，超越了现有工具。更令人振奋的是，LLMs还揭示了64个应用中24个未知的NCF错误，其中四个已得到确认或修复。尽管存在性能下降和误报等挑战，这项研究仍为LLMs在安卓NCF错误检测中的应用前景提供了有力证明，并为未来的研究方向提供了启示。

> Numerous approaches employing various strategies have been developed to test the graphical user interfaces (GUIs) of mobile apps. However, traditional GUI testing techniques, such as random and model-based testing, primarily focus on generating test sequences that excel in achieving high code coverage but often fail to act as effective test oracles for non-crash functional (NCF) bug detection. To tackle these limitations, this study empirically investigates the capability of leveraging large language models (LLMs) to be test oracles to detect NCF bugs in Android apps. Our intuition is that the training corpora of LLMs, encompassing extensive mobile app usage and bug report descriptions, enable them with the domain knowledge relevant to NCF bug detection. We conducted a comprehensive empirical study to explore the effectiveness of LLMs as test oracles for detecting NCF bugs in Android apps on 71 well-documented NCF bugs. The results demonstrated that LLMs achieve a 49% bug detection rate, outperforming existing tools for detecting NCF bugs in Android apps. Additionally, by leveraging LLMs to be test oracles, we successfully detected 24 previously unknown NCF bugs in 64 Android apps, with four of these bugs being confirmed or fixed. However, we also identified limitations of LLMs, primarily related to performance degradation, inherent randomness, and false positives. Our study highlights the potential of leveraging LLMs as test oracles for Android NCF bug detection and suggests directions for future research.

[Arxiv](https://arxiv.org/abs/2407.19053)