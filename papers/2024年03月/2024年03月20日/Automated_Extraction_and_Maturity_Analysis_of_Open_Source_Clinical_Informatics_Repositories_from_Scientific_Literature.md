# 本研究致力于自动从科学文献中挖掘开源临床信息学仓库，并对其成熟度进行深入分析，以揭示其在医疗信息领域的应用与发展状况。

发布时间：2024年03月20日

`LLM应用` `临床信息学` `科研软件管理`

> Automated Extraction and Maturity Analysis of Open Source Clinical Informatics Repositories from Scientific Literature

# 摘要

> 随着临床信息学领域的快速发展，政府资助开发的软件工具的整合与应用成为了推动研究和应用的重要突破点。然而，由于这些工具散布在众多存储库中，缺乏统一的知识平台，使得充分发掘其价值面临重大挑战。本研究提出一种创新的方法论，通过自动从arXiv收录的学术论文中抽取出GitHub仓库链接，重点关注临床信息学方向。该方法包括筛选arXiv API中的相关文献，清理提取出的GitHub地址，利用GitHub API深入获取仓库详尽信息，并基于星标数、分支数、未解决问题数和贡献者数量等标准衡量仓库成熟度。整个流程兼顾健壮性和稳定性，融入错误处理机制及速率控制，确保遵循API使用规范。初步研究结果显示，这种方法成功构建起一个汇集NIH资助软件工具的中心化知识库，为临床信息学界更全面地理解和运用这些资源铺平道路。我们进一步设想在未来引入大型语言模型（LLMs），以生成对这些工具的精炼总结和评估报告。这种途径不仅有利于发现和评价临床信息学工具，还能实时追踪新出现的和活跃更新的仓库资源，颠覆性地改变科研人员获取和利用联邦资助软件的方式。此项研究的影响远不止于简化珍贵资源的获取途径；它提出了一个适用于科研软件动态整合与评估的可扩展模型，有力推动临床信息学以及相关领域更加协同、透明和高效的科研实践。

> In the evolving landscape of clinical informatics, the integration and utilization of software tools developed through governmental funding represent a pivotal advancement in research and application. However, the dispersion of these tools across various repositories, with no centralized knowledge base, poses significant challenges to leveraging their full potential. This study introduces an automated methodology to bridge this gap by systematically extracting GitHub repository URLs from academic papers indexed in arXiv, focusing on the field of clinical informatics. Our approach encompasses querying the arXiv API for relevant papers, cleaning extracted GitHub URLs, fetching comprehensive repository information via the GitHub API, and analyzing repository maturity based on defined metrics such as stars, forks, open issues, and contributors. The process is designed to be robust, incorporating error handling and rate limiting to ensure compliance with API constraints. Preliminary findings demonstrate the efficacy of this methodology in compiling a centralized knowledge base of NIH-funded software tools, laying the groundwork for an enriched understanding and utilization of these resources within the clinical informatics community. We propose the future integration of Large Language Models (LLMs) to generate concise summaries and evaluations of the tools. This approach facilitates the discovery and assessment of clinical informatics tools and also enables ongoing monitoring of new and actively updated repositories, revolutionizing how researchers access and leverage federally funded software. The implications of this study extend beyond simplification of access to valuable resources; it proposes a scalable model for the dynamic aggregation and evaluation of scientific software, encouraging more collaborative, transparent, and efficient research practices in clinical informatics and beyond.

[Arxiv](https://arxiv.org/abs/2403.14721)