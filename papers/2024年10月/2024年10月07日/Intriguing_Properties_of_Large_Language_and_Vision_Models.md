# 大型语言与视觉模型中那些引人入胜的特性

发布时间：2024年10月07日

`LLM应用` `人工智能` `计算机视觉`

> Intriguing Properties of Large Language and Vision Models

# 摘要

> 近期，大型语言与视觉模型（LLVMs）因其卓越的泛化能力而备受瞩目，尤其在涉及感知与认知的广泛任务中表现突出。其成功秘诀在于简洁的架构：视觉编码器、投影器与大型语言模型的巧妙结合。然而，尽管在复杂推理任务中大放异彩，LLVMs 在基础感知任务（如 MMVP）上的表现却令人意外地不尽如人意。这不禁让人思考，LLVMs 究竟如何解读图像，又如何充分发挥视觉编码器的优势？为此，我们深入探究了排列不变性、鲁棒性、数学推理、对齐保持及重要性等多个维度，通过评估主流 LLVM 家族（如 LLaVA）在 10 大基准测试中的表现，揭示了其内在特性：(1) 即便视觉补丁顺序被打乱，LLVMs 仍能全局处理图像；(2) 有时无需详尽数值信息，也能解决数学难题；(3) 跨模态对齐过度适应复杂推理，却削弱了视觉编码器的原始感知力；(4) 底层表示空间（<25%）对性能与视觉理解至关重要。基于这些发现，我们展望了未来 LLVMs 的优化方向，并呼吁构建更具挑战性的评估体系。

> Recently, large language and vision models (LLVMs) have received significant attention and development efforts due to their remarkable generalization performance across a wide range of tasks requiring perception and cognitive abilities. A key factor behind their success is their simple architecture, which consists of a vision encoder, a projector, and a large language model (LLM). Despite their achievements in advanced reasoning tasks, their performance on fundamental perception-related tasks (e.g., MMVP) remains surprisingly low. This discrepancy raises the question of how LLVMs truly perceive images and exploit the advantages of the vision encoder. To address this, we systematically investigate this question regarding several aspects: permutation invariance, robustness, math reasoning, alignment preserving and importance, by evaluating the most common LLVM's families (i.e., LLaVA) across 10 evaluation benchmarks. Our extensive experiments reveal several intriguing properties of current LLVMs: (1) they internally process the image in a global manner, even when the order of visual patch sequences is randomly permuted; (2) they are sometimes able to solve math problems without fully perceiving detailed numerical information; (3) the cross-modal alignment is overfitted to complex reasoning tasks, thereby, causing them to lose some of the original perceptual capabilities of their vision encoder; (4) the representation space in the lower layers (<25%) plays a crucial role in determining performance and enhancing visual understanding. Lastly, based on the above observations, we suggest potential future directions for building better LLVMs and constructing more challenging evaluation benchmarks.

[Arxiv](https://arxiv.org/abs/2410.04751)