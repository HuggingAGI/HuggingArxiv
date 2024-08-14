# ComGPT：借助大型语言模型揭示本地社区结构

发布时间：2024年08月13日

`LLM应用` `社交网络` `社区检测`

> ComGPT: Detecting Local Community Structure with Large Language Models

# 摘要

> GPT 等大型语言模型在图结构理解和图推理任务中表现出色，但如何利用这些模型优化局部社区检测仍是一个未充分探索的领域。传统的基于种子扩展的算法存在种子依赖、社区扩散和搭便车效应等问题。为此，我们通过补充社区知识改进图编码，并设计 NSG 提示来增强模型对社区特征的理解，以缓解上述问题。我们提出的 ComGPT 方法通过迭代选择和 GPT 优化，有效提升了局部社区检测的性能。实验证明，ComGPT 在性能上超越了现有算法，验证了我们的改进措施的有效性。

> Large language models (LLMs), like GPT, have demonstrated the ability to understand graph structures and have achieved excellent performance in various graph reasoning tasks such as node classification. So far, how to leverage LLMs to better detect local communities remains underexplored. Local community detection algorithms based on seed expansion often face a seed-dependent problem, community diffusion, and free rider effect. Using LLMs to solve existing local community work problems faces the following challenges: existing graph encoding methods fail to provide LLMs with sufficient community-related graph information; LLMs lack domain knowledge in mining communities. To address these issues, we improve graph encoding by supplementing community knowledge to enhance the ability of graph encoding to express graph information. Additionally, we design the NSG (Node Selection Guide) prompt to enhance LLMs' understanding of community characteristics, aiming to alleviate the seed-dependent problem, community diffusion, and free rider effect. Based on the graph encoding and NSG prompt, we present a GPT-guided local community detection, called ComGPT. ComGPT iteratively selects potential nodes from the detected community's neighbors and subsequently employs GPT to choose the node that optimally integrates into the detected community from these selected potential nodes. Experimental results demonstrate that ComGPT outperforms the comparison algorithms, thereby confirming the effectiveness of the designed graph encoding and prompt.

[Arxiv](https://arxiv.org/abs/2408.06658)