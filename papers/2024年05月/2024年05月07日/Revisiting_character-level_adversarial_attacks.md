# 再探字符级对抗攻击：深入分析与挑战

发布时间：2024年05月07日

`Agent

解释：这篇论文介绍了一种名为Charmer的新型对抗攻击手段，它能够在自然语言处理任务中有效地进行字符级别的攻击，同时保持对抗样本的语义相似性。Charmer被设计为一种基于查询的攻击方法，它对不同规模的语言模型（如小型BERT模型和大型Llama 2模型）都显示出有效性。这种攻击手段可以被视为一种智能代理（Agent），因为它能够自主地执行攻击任务，并且能够适应不同的模型和数据集。因此，这篇论文更符合Agent分类，而不是RAG、LLM应用或LLM理论，因为它的重点在于开发和评估一种具体的攻击方法，而不是在理论层面探讨语言模型，也不是直接应用于语言模型的某个特定场景，更不是关于检索增强生成（RAG）的研究。` `网络安全`

> Revisiting character-level adversarial attacks

# 摘要

> 在自然语言处理领域，对抗性攻击通过微调字符或标记来施加影响。标记级别的攻击因其依赖梯度上升，而备受瞩目，但这也可能导致句子语义的扭曲，产生无效的对抗样本。相比之下，字符级别的攻击虽能更好地保持语义，却因难以融入主流的梯度方法而较少受到关注，且被认为防御起来相对容易。我们提出的Charmer挑战了这一观点，它是一种基于查询的高效对抗攻击手段，能够在保持对抗样本高度相似性的同时，实现显著的攻击成功率（ASR）。Charmer对小型BERT模型和大型Llama 2模型均有效。特别是在BERT模型上使用SST-2数据集时，Charmer将ASR提升了4.84个百分点，同时将USE相似性提高了8个百分点，超越了现有技术水平。我们的实现代码已公开在https://github.com/LIONS-EPFL/Charmer。

> Adversarial attacks in Natural Language Processing apply perturbations in the character or token levels. Token-level attacks, gaining prominence for their use of gradient-based methods, are susceptible to altering sentence semantics, leading to invalid adversarial examples. While character-level attacks easily maintain semantics, they have received less attention as they cannot easily adopt popular gradient-based methods, and are thought to be easy to defend. Challenging these beliefs, we introduce Charmer, an efficient query-based adversarial attack capable of achieving high attack success rate (ASR) while generating highly similar adversarial examples. Our method successfully targets both small (BERT) and large (Llama 2) models. Specifically, on BERT with SST-2, Charmer improves the ASR in 4.84% points and the USE similarity in 8% points with respect to the previous art. Our implementation is available in https://github.com/LIONS-EPFL/Charmer.

[Arxiv](https://arxiv.org/abs/2405.04346)