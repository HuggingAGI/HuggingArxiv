# EchoNarrator：为射血分数的预测生成自然文本的解释

发布时间：2024年10月31日

`LLM应用` `心脏病学`

> EchoNarrator: Generating natural text explanations for ejection fraction predictions

# 摘要

> 左心室的射血分数（EF）被视作诊断急性心力衰竭的关键指标之一，可在心脏超声采集过程中进行估算。尽管深度学习研究近来在估算 EF 值方面成果斐然，但所提模型常常对预测缺乏解释。不过，为临床测量预测提供清晰直观的阐释，会增强心脏病专家对这些模型的信任。本文中，我们探索借助自然语言解释（NLE）来预测 EF 测量。我们提出了一个模型，它在单次前向传递中，将多个帧上左心室轮廓的估算与一组用于计算与射血分数相关的各种运动和形状属性的模块及例程相结合。随后将这些属性输入大型语言模型，生成有助于以类人的方式解释网络结果的文本。我们对解释输出和 EF 预测进行了实验评估，表明我们的模型能够提供与前沿水平相当的 EF，以及对预测有意义且准确的自然语言解释。项目页面位于 https://github.com/guybenyosef/EchoNarrator 。

> Ejection fraction (EF) of the left ventricle (LV) is considered as one of the most important measurements for diagnosing acute heart failure and can be estimated during cardiac ultrasound acquisition. While recent successes in deep learning research successfully estimate EF values, the proposed models often lack an explanation for the prediction. However, providing clear and intuitive explanations for clinical measurement predictions would increase the trust of cardiologists in these models. In this paper, we explore predicting EF measurements with Natural Language Explanation (NLE). We propose a model that in a single forward pass combines estimation of the LV contour over multiple frames, together with a set of modules and routines for computing various motion and shape attributes that are associated with ejection fraction. It then feeds the attributes into a large language model to generate text that helps to explain the network's outcome in a human-like manner. We provide experimental evaluation of our explanatory output, as well as EF prediction, and show that our model can provide EF comparable to state-of-the-art together with meaningful and accurate natural language explanation to the prediction. The project page can be found at https://github.com/guybenyosef/EchoNarrator .

[Arxiv](https://arxiv.org/abs/2410.23744)