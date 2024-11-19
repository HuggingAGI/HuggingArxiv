# 自动发现并评估语义分割中的可解释性系统错误

发布时间：2024年11月16日

`其他` `自动驾驶` `图像分割`

> Automatic Discovery and Assessment of Interpretable Systematic Errors in Semantic Segmentation

# 摘要

> 这篇论文展示了一种用于找出分割模型中系统性差错的新颖办法。举例来说，分割模型里的系统性差错可能是模型把众多目标类别为行人的样本大量错分为停车计时器。鉴于这些模型在诸如自动驾驶之类的关键应用中快速投入使用，检测并阐释这些系统性差错极为重要。不过，关键难题在于自动在未标注的数据中找出此类故障，并构建可解释的语义子组以实施干预。为此，我们借助多模态基础模型来检索差错，并依据概念关联以及差错的性质来探究这些差错的系统性。我们证实了这种差错存在于在伯克利深度驾驶数据集上训练的 SOTA 分割模型（UperNet ConvNeXt 和 UperNet Swin）之中，并对该方法进行了定性和定量的基准测试，通过为这些模型找出连贯的系统性差错彰显了其有效性。我们的工作为语义分割中迄今未得到充分探索的模型分析与干预开辟了新途径。

> This paper presents a novel method for discovering systematic errors in segmentation models. For instance, a systematic error in the segmentation model can be a sufficiently large number of misclassifications from the model as a parking meter for a target class of pedestrians. With the rapid deployment of these models in critical applications such as autonomous driving, it is vital to detect and interpret these systematic errors. However, the key challenge is automatically discovering such failures on unlabelled data and forming interpretable semantic sub-groups for intervention. For this, we leverage multimodal foundation models to retrieve errors and use conceptual linkage along with erroneous nature to study the systematic nature of these errors. We demonstrate that such errors are present in SOTA segmentation models (UperNet ConvNeXt and UperNet Swin) trained on the Berkeley Deep Drive and benchmark the approach qualitatively and quantitatively, showing its effectiveness by discovering coherent systematic errors for these models. Our work opens up the avenue to model analysis and intervention that have so far been underexplored in semantic segmentation.

[Arxiv](https://arxiv.org/abs/2411.10845)