# 持续的 LLaVA：大型视觉语言模型中的持续指令调整

发布时间：2024年11月04日

`LLM应用` `计算机视觉` `人工智能`

> Continual LLaVA: Continual Instruction Tuning in Large Vision-Language Models

# 摘要

> 指令调整是一种常见的技术，用于定制大型视觉语言模型（LVLMs）以满足个别任务的要求。到目前为止，大多数现有的方法都局限于单任务适应，而现实场景中的要求本质上是多样的并且不断变化。因此，理想的 LVLM 应该在面对流任务分布（即不同的领域、新兴的能力和新的数据集）时持续进行指令调整，同时最大限度地减少先前获得知识的遗忘。为了实现这一目标，我们为 LVLMs 的持续指令调整提出了一个新的基准 COntinuAl inStruction Tuning on LVLMs（COAST），它包括上述的领域增量、能力增量和数据集增量配置。在方法方面，我们提出了 Continual LLaVA，这是一种为 LVLMs 中的持续指令调整量身定制的无排练方法。为了避免与经验重放相关的额外开销，我们冻结 LVLMs，并为每个输入指令构建双重增量嵌入，以促进参数高效调整。具体来说，增量嵌入可以分解为两个主要组成部分：1）内在增量嵌入用于编码特定任务的特征。为了实现这一点，我们建立了一个包含候选嵌入的低秩池，根据它们与用户指令的相似性从中选择相关的嵌入；2）上下文增量嵌入用于研究任务之间的相互依赖关系。在这方面，通过可学习的加权和聚合先前任务中选择的低秩嵌入，以提供补充提示。大量实验表明，所提出的 Continual LLaVA 在持续指令调整过程中显著减少遗忘，优于以前的方法。

> Instruction tuning constitutes a prevalent technique for tailoring Large Vision Language Models (LVLMs) to meet individual task requirements. To date, most of the existing approaches are confined to single-task adaptation, whereas the requirements in real-world scenarios are inherently varied and continually evolving. Thus an ideal LVLM should sustain continual instruction tuning in the face of stream-task distributions (i.e., different domains, emerging capabilities, and new datasets) while minimizing the forgetting of previously acquired knowledge. To achieve this, we propose a new benchmark for COntinuAl inStruction Tuning on LVLMs (COAST), which encompasses the aforementioned domain-incremental, capability-incremental, and dataset-incremental configurations. In terms of methodology, we propose Continual LLaVA, a rehearsal-free method tailored for continual instruction tuning in LVLMs. To circumvent the additional overhead associated with experience replay, we freeze LVLMs and construct the dual increment embeddings for each input instruction to facilitate parameter-efficient tuning. Specifically, the increment embeddings can be decomposed into two principal components: 1) intrinsic increment embeddings to encode task-specific characteristics. To achieve this, we set up a low-rank pool containing candidate embeddings, from which we select the relevant ones based on their similarity with the user instructions; 2) contextual increment embeddings to investigate the inter-dependencies across tasks. In this regard, the low-rank embeddings chosen in the previous tasks are aggregated via learnable weighted sum to provide complementary hints. Extensive experiments indicate that the proposed Continual LLaVA outperforms previous methods by significantly reducing the forgetting during the continual instruction tuning process.

[Arxiv](https://arxiv.org/abs/2411.02564)