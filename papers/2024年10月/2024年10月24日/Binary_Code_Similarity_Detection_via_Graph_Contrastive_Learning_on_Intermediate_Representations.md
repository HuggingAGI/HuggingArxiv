# 通过中间表示上的图对比学习进行二进制代码相似性检测

发布时间：2024年10月24日

`LLM应用` `软件安全` `物联网`

> Binary Code Similarity Detection via Graph Contrastive Learning on Intermediate Representations

# 摘要

> 二进制代码相似性检测（BCSD）在众多领域发挥着关键作用，包括漏洞检测、恶意软件分析和代码复用识别。随着物联网设备的激增和快速发展，它们高度异构的硬件架构和复杂的编译设置，再加上实际应用中对大规模函数检索的需求，对 BCSD 方法提出了更高的要求。在本文中，我们提出了 IRBinDiff，它通过利用具有更高级语义抽象的 LLVM-IR 来减轻编译差异，并将预训练语言模型与图神经网络集成，从不同角度捕获语义和结构信息。通过引入动量对比学习，它有效地增强了在大规模候选函数集中的检索能力，区分细微的函数相似性和差异。我们在各种编译设置下进行的大量实验表明，IRBinDiff 在一对一比较和一对多搜索场景中都优于其他领先的 BCSD 方法。

> Binary Code Similarity Detection (BCSD) plays a crucial role in numerous fields, including vulnerability detection, malware analysis, and code reuse identification. As IoT devices proliferate and rapidly evolve, their highly heterogeneous hardware architectures and complex compilation settings, coupled with the demand for large-scale function retrieval in practical applications, put forward higher requirements for BCSD methods. In this paper, we propose IRBinDiff, which mitigates compilation differences by leveraging LLVM-IR with higher-level semantic abstraction, and integrates a pre-trained language model with a graph neural network to capture both semantic and structural information from different perspectives. By introducing momentum contrastive learning, it effectively enhances retrieval capabilities in large-scale candidate function sets, distinguishing between subtle function similarities and differences. Our extensive experiments, conducted under varied compilation settings, demonstrate that IRBinDiff outperforms other leading BCSD methods in both One-to-one comparison and One-to-many search scenarios.

[Arxiv](https://arxiv.org/abs/2410.18561)