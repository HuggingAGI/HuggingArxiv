# 金字塔驱动对齐：以金字塔原则为指导，整合大型语言模型与知识图谱

发布时间：2024年10月16日

`LLM应用` `知识图谱` `问答系统`

> Pyramid-Driven Alignment: Pyramid Principle Guided Integration of Large Language Models and Knowledge Graphs

# 摘要

> 大型语言模型 (LLM) 虽推理能力出众，但常生成错误信息，即所谓的“幻觉”。现有方法虽尝试通过结合外部知识图谱 (KG) 来缓解此问题，但多将 KG 视为静态知识库，忽视了 KG 与 LLM 知识间的关键差异，未能充分挖掘 KG 的推理潜力。为此，我们创新性地提出了金字塔驱动对齐 (PDA) 框架，旨在无缝融合 LLM 与 KG。PDA 通过金字塔原则分析，构建层次化结构，精准映射输入问题，生成更可靠的演绎知识，从而强化 LLM 与 KG 的协同，实现更紧密的集成。此外，PDA 引入递归机制，深度挖掘 KG 的推理能力，显著提升问答任务中的知识检索准确性。实验结果表明，PDA 性能远超现有最先进基线，提升幅度高达 26.70% 和 26.78%。

> Large Language Models (LLMs) possess impressive reasoning abilities but are prone to generating incorrect information, often referred to as hallucinations. While incorporating external Knowledge Graphs (KGs) can partially mitigate this issue, existing methods primarily treat KGs as static knowledge repositories, overlooking the critical disparity between KG and LLM knowledge, and failing to fully exploit the reasoning capabilities inherent in KGs. To address these limitations, we propose Pyramid-Driven Alignment (PDA), a novel framework for seamlessly integrating LLMs with KGs. PDA utilizes Pyramid Principle analysis to construct a hierarchical pyramid structure. This structure is designed to reflect the input question and generate more validated deductive knowledge, thereby enhancing the alignment of LLMs and KGs and ensuring more cohesive integration. Furthermore, PDA employs a recursive mechanism to harness the underlying reasoning abilities of KGs, resulting in more accurate knowledge retrieval for question-answering tasks. Our experimental results reveal a substantial performance advantage of PDA over state-of-the-art baselines, with improvements reaching 26.70% and 26.78%.

[Arxiv](https://arxiv.org/abs/2410.12298)