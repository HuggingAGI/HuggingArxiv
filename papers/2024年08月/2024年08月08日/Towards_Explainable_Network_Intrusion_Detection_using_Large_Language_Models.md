# 探索利用大型语言模型实现网络入侵检测的可解释性

发布时间：2024年08月08日

`Agent` `网络安全` `威胁检测`

> Towards Explainable Network Intrusion Detection using Large Language Models

# 摘要

> 大型语言模型（LLM）在自然语言处理领域，尤其是作为聊天代理，已经带来了革命性的变化。然而，它们在威胁检测领域的应用尚不明朗。本文探讨了将LLM作为网络入侵检测系统（NIDS）的可行性，尽管其高计算需求，主要出于解释性的考虑。当前最先进的NIDS依赖人工基准数据集，导致在真实网络环境中的性能偏差。因此，我们比较了GPT-4和LLama3模型与传统及基于转换器的模型，评估它们仅凭预训练知识检测恶意NetFlow的能力。结果表明，尽管LLM在精确攻击检测上存在挑战，但在构建可解释的NIDS方面潜力巨大。初步探索显示，LLM不适用于恶意NetFlow的检测，但作为NIDS的补充代理，特别是在与RAG和功能调用集成时提供解释和辅助威胁响应方面，显示出显著潜力。

> Large Language Models (LLMs) have revolutionised natural language processing tasks, particularly as chat agents. However, their applicability to threat detection problems remains unclear. This paper examines the feasibility of employing LLMs as a Network Intrusion Detection System (NIDS), despite their high computational requirements, primarily for the sake of explainability. Furthermore, considerable resources have been invested in developing LLMs, and they may offer utility for NIDS. Current state-of-the-art NIDS rely on artificial benchmarking datasets, resulting in skewed performance when applied to real-world networking environments. Therefore, we compare the GPT-4 and LLama3 models against traditional architectures and transformer-based models to assess their ability to detect malicious NetFlows without depending on artificially skewed datasets, but solely on their vast pre-trained acquired knowledge. Our results reveal that, although LLMs struggle with precise attack detection, they hold significant potential for a path towards explainable NIDS. Our preliminary exploration shows that LLMs are unfit for the detection of Malicious NetFlows. Most promisingly, however, these exhibit significant potential as complementary agents in NIDS, particularly in providing explanations and aiding in threat response when integrated with Retrieval Augmented Generation (RAG) and function calling capabilities.

[Arxiv](https://arxiv.org/abs/2408.04342)