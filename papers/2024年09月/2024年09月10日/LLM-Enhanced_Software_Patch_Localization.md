# 大型语言模型增强的软件补丁定位

发布时间：2024年09月10日

`LLM应用` `软件开发` `网络安全`

> LLM-Enhanced Software Patch Localization

# 摘要

> 开源软件 (OSS) 在现代产品开发中不可或缺，但其漏洞可能波及众多产品。尽管开发者努力修复，但在海量更新中定位安全补丁仍具挑战。为此，我们推出了 LLM-SPL，一种利用大型语言模型 (LLM) 能力的推荐方法，精准定位安全补丁。实验表明，LLM-SPL 在召回率和人工效率上均优于现有技术，尤其在多补丁漏洞处理上表现突出，召回率提升 22.83%，NDCG 提升 19.41%，人工检查减少 25% 以上。数据集和代码已公开，详见 \url{https://anonymous.4open.science/r/LLM-SPL-91F8}。

> Open source software (OSS) is integral to modern product development, and any vulnerability within it potentially compromises numerous products. While developers strive to apply security patches, pinpointing these patches among extensive OSS updates remains a challenge. Security patch localization (SPL) recommendation methods are leading approaches to address this. However, existing SPL models often falter when a commit lacks a clear association with its corresponding CVE, and do not consider a scenario that a vulnerability has multiple patches proposed over time before it has been fully resolved. To address these challenges, we introduce LLM-SPL, a recommendation-based SPL approach that leverages the capabilities of the Large Language Model (LLM) to locate the security patch commit for a given CVE. More specifically, we propose a joint learning framework, in which the outputs of LLM serves as additional features to aid our recommendation model in prioritizing security patches. Our evaluation on a dataset of 1,915 CVEs associated with 2,461 patches demonstrates that LLM-SPL excels in ranking patch commits, surpassing the state-of-the-art method in terms of Recall, while significantly reducing manual effort. Notably, for vulnerabilities requiring multiple patches, LLM-SPL significantly improves Recall by 22.83\%, NDCG by 19.41\%, and reduces manual effort by over 25\% when checking up to the top 10 rankings. The dataset and source code are available at \url{https://anonymous.4open.science/r/LLM-SPL-91F8}.

[Arxiv](https://arxiv.org/abs/2409.06816)