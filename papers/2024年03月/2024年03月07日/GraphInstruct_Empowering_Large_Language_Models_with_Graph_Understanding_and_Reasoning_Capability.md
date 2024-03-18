# GraphInstruct 是一项技术，它赋予大型语言模型强大的图理解和推理能力。

发布时间：2024年03月07日

`LLM应用`

> GraphInstruct: Empowering Large Language Models with Graph Understanding and Reasoning Capability

> 近年来，提升大型语言模型（LLMs）处理各类任务的一般能力成为了研究热点。鉴于图结构在现实生活中的广泛应用以及对图数据理解对于推进人工智能发展的关键作用，本研究致力于评估和强化LLMs对图数据的理解力。为此，我们创新设计了一个名为GraphInstruct的基准评测集，整合了21个经典图推理任务，提供多种图形生成流程及详尽推理步骤。在此基础上，我们通过高效指令调优技术打造出GraphLM模型，其在图理解方面展现出了卓越性能。不仅如此，为深化LLMs的图推理能力，我们又提出了阶段掩码训练策略，并构建出GraphLM+模型。广泛的实验验证表明，GraphLM与GraphLM+在图理解和推理上明显优于其他LLMs，堪称该领域的先行者。我们已将用于生成GraphInstruct的源代码公开发布在GitHub（https://github.com/CGCL-codes/GraphInstruct），期待更多研究者借此平台发掘LLMs在图数据挖掘领域的巨大潜能。

> Evaluating and enhancing the general capabilities of large language models (LLMs) has been an important research topic. Graph is a common data structure in the real world, and understanding graph data is a crucial part for advancing general intelligence. To evaluate and enhance the graph understanding abilities of LLMs, in this paper, we propose a benchmark named GraphInstruct, which comprehensively includes 21 classical graph reasoning tasks, providing diverse graph generation pipelines and detailed reasoning steps. Based on GraphInstruct, we further construct GraphLM through efficient instruction-tuning, which shows prominent graph understanding capability. In order to enhance the LLM with graph reasoning capability as well, we propose a step mask training strategy, and construct a model named GraphLM+. As one of the pioneering efforts to enhance the graph understanding and reasoning abilities of LLMs, extensive experiments have demonstrated the superiority of GraphLM and GraphLM+ over other LLMs. We look forward to more researchers exploring the potential of LLMs in the graph data mining domain through GraphInstruct. Our code for generating GraphInstruct is released publicly at: https://github.com/CGCL-codes/GraphInstruct.

[Arxiv](https://arxiv.org/abs/2403.04483)