# FRAG：协作与安全检索增强生成的联邦向量数据库管理

发布时间：2024年10月17日

`RAG` `数据库管理` `数据隐私`

> FRAG: Toward Federated Vector Database Management for Collaborative and Secure Retrieval-Augmented Generation

# 摘要

> 本文推出了一种名为 \textit{Federated Retrieval-Augmented Generation (FRAG)} 的新型数据库管理范式，专为日益依赖大型语言模型 (LLM) 的检索增强生成 (RAG) 系统设计。FRAG 让互不信任的各方能在加密数据上协作进行近似 $k$-最近邻搜索，同时确保数据隐私。实现这一目标面临两大挑战：一是确保实际条件下的强大安全保障，二是保持与传统系统相当的性能。为此，FRAG 采用单一密钥同态加密简化密钥管理，并引入乘法缓存技术提升浮点数加密效率。通过严格的安全证明和广泛实验，我们验证了 FRAG 在大规模环境中的实用性和高效性。

> This paper introduces \textit{Federated Retrieval-Augmented Generation (FRAG)}, a novel database management paradigm tailored for the growing needs of retrieval-augmented generation (RAG) systems, which are increasingly powered by large-language models (LLMs). FRAG enables mutually-distrusted parties to collaboratively perform Approximate $k$-Nearest Neighbor (ANN) searches on encrypted query vectors and encrypted data stored in distributed vector databases, all while ensuring that no party can gain any knowledge about the queries or data of others. Achieving this paradigm presents two key challenges: (i) ensuring strong security guarantees, such as Indistinguishability under Chosen-Plaintext Attack (IND-CPA), under practical assumptions (e.g., we avoid overly optimistic assumptions like non-collusion among parties); and (ii) maintaining performance overheads comparable to traditional, non-federated RAG systems. To address these challenges, FRAG employs a single-key homomorphic encryption protocol that simplifies key management across mutually-distrusted parties. Additionally, FRAG introduces a \textit{multiplicative caching} technique to efficiently encrypt floating-point numbers, significantly improving computational performance in large-scale federated environments. We provide a rigorous security proof using standard cryptographic reductions and demonstrate the practical scalability and efficiency of FRAG through extensive experiments on both benchmark and real-world datasets.

[Arxiv](https://arxiv.org/abs/2410.13272)