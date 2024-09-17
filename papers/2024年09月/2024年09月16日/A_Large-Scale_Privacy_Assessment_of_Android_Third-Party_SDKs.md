# 大规模评估 Android 第三方 SDK 的隐私状况

发布时间：2024年09月16日

`LLM应用` `移动应用开发` `隐私保护`

> A Large-Scale Privacy Assessment of Android Third-Party SDKs

# 摘要

> 第三方 SDK 在 Android 应用开发中广泛使用，旨在加速开发并增强功能。然而，这种便利也带来了用户隐私信息被非法访问和滥用的风险。我们的研究深入分析了 Android 第三方 SDK 的隐私保护问题，填补了软件供应链中的重要空白。研究聚焦于数据外泄和隐私合规性，通过污点分析和大型语言模型技术，对两大平台上的 158 个常用 SDK 进行了调查。结果显示，338 例隐私数据外泄，超过 30% 的 SDK 缺乏隐私政策，其中 37% 过度收集数据，88% 虚假声称访问敏感数据。12 个月后，这些趋势仍未改善。基于此，我们提出三项建议，以降低隐私泄露风险，加强用户保护。我们的研究不仅呼吁行业重视，也为未来监管提供了重要参考。

> Third-party Software Development Kits (SDKs) are widely adopted in Android app development, to effortlessly accelerate development pipelines and enhance app functionality. However, this convenience raises substantial concerns about unauthorized access to users' privacy-sensitive information, which could be further abused for illegitimate purposes like user tracking or monetization. Our study offers a targeted analysis of user privacy protection among Android third-party SDKs, filling a critical gap in the Android software supply chain. It focuses on two aspects of their privacy practices, including data exfiltration and behavior-policy compliance (or privacy compliance), utilizing techniques of taint analysis and large language models. It covers 158 widely-used SDKs from two key SDK release platforms, the official one and a large alternative one. From them, we identified 338 instances of privacy data exfiltration. On the privacy compliance, our study reveals that more than 30% of the examined SDKs fail to provide a privacy policy to disclose their data handling practices. Among those that provide privacy policies, 37% of them over-collect user data, and 88% falsely claim access to sensitive data. We revisit the latest versions of the SDKs after 12 months. Our analysis demonstrates a persistent lack of improvement in these concerning trends. Based on our findings, we propose three actionable recommendations to mitigate the privacy leakage risks and enhance privacy protection for Android users. Our research not only serves as an urgent call for industry attention but also provides crucial insights for future regulatory interventions.

[Arxiv](https://arxiv.org/abs/2409.10411)