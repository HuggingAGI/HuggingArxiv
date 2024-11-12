# 隐藏在显而易见之中：评估视觉语言模型中的抽象形状识别

发布时间：2024年11月09日

`LLM应用` `计算机视觉` `图像分类`

> Hidden in Plain Sight: Evaluating Abstract Shape Recognition in Vision-Language Models

# 摘要

> 尽管形状感知在人类视觉中很重要，但早期的神经图像分类器在对象识别中对形状信息的依赖程度低于其他（通常是虚假的）特征。虽然最近的研究表明，当前的大型视觉语言模型（VLMs）对形状的依赖程度更高，但我们发现它们在这方面仍然受到严重限制。为了量化这种限制，我们引入了 IllusionBench，这是一个数据集，它挑战当前最先进的 VLMs 在场景中视觉元素的排列表示形状时解读形状信息。我们的广泛评估表明，虽然这些形状很容易被人类注释者检测到，但当前的 VLMs 很难识别它们，这为开发更强大的视觉感知系统的未来工作指明了重要方向。完整的数据集和代码库可在以下网址获取：url{https://arshiahemmat.github.io/illusionbench/}

> Despite the importance of shape perception in human vision, early neural image classifiers relied less on shape information for object recognition than other (often spurious) features. While recent research suggests that current large Vision-Language Models (VLMs) exhibit more reliance on shape, we find them to still be seriously limited in this regard. To quantify such limitations, we introduce IllusionBench, a dataset that challenges current cutting-edge VLMs to decipher shape information when the shape is represented by an arrangement of visual elements in a scene. Our extensive evaluations reveal that, while these shapes are easily detectable by human annotators, current VLMs struggle to recognize them, indicating important avenues for future work in developing more robust visual perception systems. The full dataset and codebase are available at: url{https://arshiahemmat.github.io/illusionbench/}

[Arxiv](https://arxiv.org/abs/2411.06287)