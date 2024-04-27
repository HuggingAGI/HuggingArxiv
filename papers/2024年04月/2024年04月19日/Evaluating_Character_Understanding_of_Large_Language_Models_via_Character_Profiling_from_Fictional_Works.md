# 本研究通过分析虚构作品中的角色档案，探讨了大型语言模型对角色认知的深度。

发布时间：2024年04月19日

`分类：Agent

这篇论文讨论了大型语言模型（LLMs）在角色扮演代理（RPAs）中的应用，特别是它们如何理解和塑造虚构角色。论文提出了一种新的评价方法，通过角色画像任务来衡量LLMs对角色的理解力。这表明论文的重点是LLMs在特定应用领域（即RPAs）的性能和应用，因此将其归类为Agent。` `人工智能`

> Evaluating Character Understanding of Large Language Models via Character Profiling from Fictional Works

# 摘要

> 大型语言模型（LLMs）以其卓越的性能引领了众多AI应用的潮流，其中角色扮演代理（RPAs）因其独特的魅力而备受青睐，尤其是在虚构角色的塑造上。RPAs的核心在于LLMs对虚构作品中角色的深刻理解。尽管以往的研究尝试通过基础分类或特征模仿任务来评估LLMs的这一能力，但这些方法并未能充分捕捉到LLMs对角色理解的细腻之处。本文提出了一种新的评价方法——通过角色画像任务来衡量LLMs对角色的理解力，即从相关材料中提炼出角色画像，这一方法在RPAs的发展中虽被广泛应用，却鲜少受到学术界的关注。我们特别构建了CroSS数据集，并邀请文学专家参与，通过比对基准真实参考和角色画像在下游任务中的应用性来评估生成的画像。我们进行的一系列实验，包括多种总结方法和LLMs的测试，均取得了令人鼓舞的成果，这些成果充分证实了LLMs在角色理解方面的能力。我们期望本研究能够为该领域的深入探索提供动力。相关资源已在 https://github.com/Joanna0123/character_profiling 上发布。

> Large language models (LLMs) have demonstrated impressive performance and spurred numerous AI applications, in which role-playing agents (RPAs) are particularly popular, especially for fictional characters. The prerequisite for these RPAs lies in the capability of LLMs to understand characters from fictional works. Previous efforts have evaluated this capability via basic classification tasks or characteristic imitation, failing to capture the nuanced character understanding with LLMs. In this paper, we propose evaluating LLMs' character understanding capability via the character profiling task, i.e., summarizing character profiles from corresponding materials, a widely adopted yet understudied practice for RPA development. Specifically, we construct the CroSS dataset from literature experts and assess the generated profiles by comparing ground truth references and their applicability in downstream tasks. Our experiments, which cover various summarization methods and LLMs, have yielded promising results. These results strongly validate the character understanding capability of LLMs. We believe our constructed resource will promote further research in this field. Resources are available at https://github.com/Joanna0123/character_profiling.

[Arxiv](https://arxiv.org/abs/2404.12726)