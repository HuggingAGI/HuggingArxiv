# PackageIntel：借助大型语言模型，实现包生态系统中的智能自动化提取

发布时间：2024年09月23日

`LLM应用` `软件供应链安全` `网络安全`

> PackageIntel: Leveraging Large Language Models for Automated Intelligence Extraction in Package Ecosystems

# 摘要

> 公共注册表中的恶意包激增，对软件供应链安全构成严重威胁。尽管业界采用SCA等方法应对，但现有手段往往情报更新不及时、不全面。本文推出的PackageIntel平台，通过穷举搜索、多源滚雪球抽样及LLM专用提示，彻底革新了恶意包情报的收集与处理。我们构建了包含20,692个恶意NPM和PyPI包的数据库，覆盖21个情报源。实测显示，PackageIntel情报提取精度达98.6%，F1分数92.0，比Snyk和OSV等数据库早70%发现威胁，且每条情报成本仅0.094美元。该平台已成功在下游镜像注册表中识别并报告了1,000多个恶意包。本研究为软件供应链安全提供了高效、及时的威胁识别与缓解方案。

> The rise of malicious packages in public registries poses a significant threat to software supply chain (SSC) security. Although academia and industry employ methods like software composition analysis (SCA) to address this issue, existing approaches often lack timely and comprehensive intelligence updates. This paper introduces PackageIntel, a novel platform that revolutionizes the collection, processing, and retrieval of malicious package intelligence. By utilizing exhaustive search techniques, snowball sampling from diverse sources, and large language models (LLMs) with specialized prompts, PackageIntel ensures enhanced coverage, timeliness, and accuracy. We have developed a comprehensive database containing 20,692 malicious NPM and PyPI packages sourced from 21 distinct intelligence repositories. Empirical evaluations demonstrate that PackageIntel achieves a precision of 98.6% and an F1 score of 92.0 in intelligence extraction. Additionally, it detects threats on average 70% earlier than leading databases like Snyk and OSV, and operates cost-effectively at $0.094 per intelligence piece. The platform has successfully identified and reported over 1,000 malicious packages in downstream package manager mirror registries. This research provides a robust, efficient, and timely solution for identifying and mitigating threats within the software supply chain ecosystem.

[Arxiv](https://arxiv.org/abs/2409.15049)