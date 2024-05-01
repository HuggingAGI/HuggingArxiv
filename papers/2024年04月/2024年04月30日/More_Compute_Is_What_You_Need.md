# 计算资源，多多益善。

发布时间：2024年04月30日

`LLM理论` `计算优化`

> More Compute Is What You Need

# 摘要

> 随着大型语言模型预训练成本的不断攀升，业界普遍依据规模法则来决定模型规模和训练令牌的计算资源分配，这一方法常被称作“计算最优化”或“栗鼠最优化”。本文提出了一个新的规模法则假设，认为模型性能主要取决于在变换器模型上的计算投入，而非模型大小或数据集大小的具体分配。基于这一统一法则，我们预测：(a) 为了提升推理效率，训练时应更倾向于选择较小的模型尺寸和更庞大的训练数据集；(b) 在现有网络数据集资源耗尽的情况下，增加模型尺寸可能是进一步提升模型性能的唯一途径。

> Large language model pre-training has become increasingly expensive, with most practitioners relying on scaling laws to allocate compute budgets for model size and training tokens, commonly referred to as Compute-Optimal or Chinchilla Optimal. In this paper, we hypothesize a new scaling law that suggests model performance depends mostly on the amount of compute spent for transformer-based models, independent of the specific allocation to model size and dataset size. Using this unified scaling law, we predict that (a) for inference efficiency, training should prioritize smaller model sizes and larger training datasets, and (b) assuming the exhaustion of available web datasets, scaling the model size might be the only way to further improve model performance.

[Arxiv](https://arxiv.org/abs/2404.19484)