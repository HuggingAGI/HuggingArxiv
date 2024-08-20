# 分子几何信息引导的标记化技术，助力语言模型生成

发布时间：2024年08月19日

`LLM应用`

> Geometry Informed Tokenization of Molecules for Language Model Generation

# 摘要

> 我们探索了利用语言模型在三维空间中生成分子的可能性，这一过程需要对分子三维结构进行离散化处理。虽然分子图的标记化已有研究，但三维结构的标记化仍待深入。为此，我们提出了 Geo2Seq 方法，将分子几何结构转化为 $SE(3)$-不变的一维离散序列。Geo2Seq 通过规范标记和球面不变表示步骤，确保了几何和原子信息的完整性，并优化了语言模型的处理格式。实验结果显示，结合 Geo2Seq 后，多种语言模型在分子几何生成任务中表现卓越，尤其是在精确控制生成方面。

> We consider molecule generation in 3D space using language models (LMs), which requires discrete tokenization of 3D molecular geometries. Although tokenization of molecular graphs exists, that for 3D geometries is largely unexplored. Here, we attempt to bridge this gap by proposing the Geo2Seq, which converts molecular geometries into $SE(3)$-invariant 1D discrete sequences. Geo2Seq consists of canonical labeling and invariant spherical representation steps, which together maintain geometric and atomic fidelity in a format conducive to LMs. Our experiments show that, when coupled with Geo2Seq, various LMs excel in molecular geometry generation, especially in controlled generation tasks.

[Arxiv](https://arxiv.org/abs/2408.10120)