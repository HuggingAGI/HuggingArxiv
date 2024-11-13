# 精度的缩放定律

发布时间：2024年11月07日

`LLM理论` `语言模型` `模型训练`

> Scaling Laws for Precision

# 摘要

> 摘要：低精度训练和推理既影响语言模型的质量又影响其成本，但当前的缩放定律并未考虑到这一点。在这项工作中，我们为训练和推理设计了“精度感知”的缩放定律。我们提出，低精度训练会降低模型的“有效参数数量”，使我们能够预测低精度训练和训练后量化所产生的额外损失。对于推理，我们发现随着模型在更多数据上进行训练，训练后量化引入的性能下降会增加，最终使额外的预训练数据产生负面影响。对于训练，我们的缩放定律使我们能够预测不同精度下不同部分的模型的损失，并表明以较低精度训练更大的模型可能在计算上是最优的。我们统一了训练后和预训练量化的缩放定律，得出了一个单一的函数形式，用于预测不同精度下训练和推理的性能下降。我们对超过 465 次预训练运行进行了拟合，并在模型规模高达 17 亿参数、在多达 260 亿个标记上训练的模型上验证了我们的预测。

> 
Abstract:Low precision training and inference affect both the quality and cost of language models, but current scaling laws do not account for this. In this work, we devise "precision-aware" scaling laws for both training and inference. We propose that training in lower precision reduces the model's "effective parameter count," allowing us to predict the additional loss incurred from training in low precision and post-train quantization. For inference, we find that the degradation introduced by post-training quantization increases as models are trained on more data, eventually making additional pretraining data actively harmful. For training, our scaling laws allow us to predict the loss of a model with different parts in different precisions, and suggest that training larger models in lower precision may be compute optimal. We unify the scaling laws for post and pretraining quantization to arrive at a single functional form that predicts degradation from training and inference in varied precisions. We fit on over 465 pretraining runs and validate our predictions on model sizes up to 1.7B parameters trained on up to 26B tokens.
    

[Arxiv](https://arxiv.org/pdf/2411.04330)