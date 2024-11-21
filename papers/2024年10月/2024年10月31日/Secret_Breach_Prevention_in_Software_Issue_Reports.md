# 软件问题报告中的秘密防泄露

发布时间：2024年10月31日

`LLM应用` `软件安全` `软件开发`

> Secret Breach Prevention in Software Issue Reports

# 摘要

> 在数字时代，敏感信息的暴露给安全带来重大威胁。借助 GitHub、BitBucket 这类普及的代码共享平台，开发人员常意外泄露凭证和 API 密钥，致使关键系统被未授权访问。虽然有检测源代码中此类违规的工具，但在软件问题报告里检测秘密违规基本未被涉足。本文呈现了一种将语言模型与先进正则表达式结合的软件问题报告中秘密违规检测新技法。我们突出了诸如日志文件、URL、提交 ID、堆栈跟踪和虚拟密码等噪声带来的挑战，它们让检测过程变得复杂。通过运用相关预处理技术并借助高级语言模型的能力，我们意在有效降低潜在违规。从现有关于秘密检测工具和方法的研究中获取灵感，我们提出了一种融合先进正则表达式优势与语言模型上下文理解的办法。我们的方法旨在减少误报，提升软件问题报告中秘密违规检测的准确性。我们整理了一个包含 25000 个实例的基准数据集，其中仅 437 个为真阳性。尽管数据严重倾斜，但我们的模型表现出色，F1 分数达 0.6347，而先进的正则表达式几乎只能拿到 0.0341 的 F1 分数，精度得分也很低。我们还为 GitHub 开发了一款秘密违规缓解工具，若发布的问题报告中存在秘密，它会向用户发出警告。通过填补当代研究中的这一关键空缺，我们的工作旨在强化软件开发实践的整体安全态势。

> In the digital age, the exposure of sensitive information poses a significant threat to security. Leveraging the ubiquitous nature of code-sharing platforms like GitHub and BitBucket, developers often accidentally disclose credentials and API keys, granting unauthorized access to critical systems. Despite the availability of tools for detecting such breaches in source code, detecting secret breaches in software issue reports remains largely unexplored. This paper presents a novel technique for secret breach detection in software issue reports using a combination of language models and state-of-the-art regular expressions. We highlight the challenges posed by noise, such as log files, URLs, commit IDs, stack traces, and dummy passwords, which complicate the detection process. By employing relevant pre-processing techniques and leveraging the capabilities of advanced language models, we aim to mitigate potential breaches effectively. Drawing insights from existing research on secret detection tools and methodologies, we propose an approach combining the strengths of state-of-the-art regexes with the contextual understanding of language models. Our method aims to reduce false positives and improve the accuracy of secret breach detection in software issue reports. We have curated a benchmark dataset of 25000 instances with only 437 true positives. Although the data is highly skewed, our model performs well with a 0.6347 F1-score, whereas state-of-the-art regular expression hardly manages to get a 0.0341 F1-Score with a poor precision score. We have also developed a secret breach mitigator tool for GitHub, which will warn the user if there is any secret in the posted issue report. By addressing this critical gap in contemporary research, our work aims at enhancing the overall security posture of software development practices.

[Arxiv](https://arxiv.org/abs/2410.23657)