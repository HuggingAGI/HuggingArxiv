# 具有指数移动平均系数学习的预测-校正增强型 Transformer

发布时间：2024年11月05日

`LLM应用` `机器翻译`

> Predictor-Corrector Enhanced Transformers with Exponential Moving Average Coefficient Learning

# 摘要

> 残差网络作为常微分方程（ODEs）的离散近似，激发了神经网络设计的重大进展，包括多步方法、高阶方法和多粒子动力系统。ODEs 解的精度显著影响参数优化，从而影响模型性能。在这项工作中，我们对 Transformer 架构设计进行了一系列高级探索，以最小化与真正的“解”相比的误差。首先，我们引入了一个预测-校正学习框架来最小化截断误差，它由一个高阶预测器和一个多步校正器组成。其次，我们提出了一种基于指数移动平均的系数学习方法来强化我们的高阶预测器。在大规模机器翻译、抽象摘要、语言建模和自然语言理解基准上的大量实验证明了我们方法的优越性。在 WMT'14 英语 - 德语和英语 - 法语任务中，我们的模型分别取得了 30.95 和 44.27 的 BLEU 分数。此外，在 OPUS 多语言机器翻译任务中，我们的模型仅使用 1/3 的参数，平均比强大的 3.8B DeepNet 高出 2.9 SacreBLEU。值得注意的是，在 LM Harness 评估中，它的准确率也比 LLama 模型高出 5.7 个点。

> Residual networks, as discrete approximations of Ordinary Differential Equations (ODEs), have inspired significant advancements in neural network design, including multistep methods, high-order methods, and multi-particle dynamical systems. The precision of the solution to ODEs significantly affects parameter optimization, thereby impacting model performance. In this work, we present a series of advanced explorations of Transformer architecture design to minimize the error compared to the true ``solution.'' First, we introduce a predictor-corrector learning framework to minimize truncation errors, which consists of a high-order predictor and a multistep corrector. Second, we propose an exponential moving average-based coefficient learning method to strengthen our higher-order predictor. Extensive experiments on large-scale machine translation, abstractive summarization, language modeling, and natural language understanding benchmarks demonstrate the superiority of our approach. On the WMT'14 English-German and English-French tasks, our model achieved BLEU scores of 30.95 and 44.27, respectively. Furthermore, on the OPUS multilingual machine translation task, our model surpasses a robust 3.8B DeepNet by an average of 2.9 SacreBLEU, using only 1/3 parameters. Notably, it also beats LLama models by 5.7 accuracy points on the LM Harness Evaluation.

[Arxiv](https://arxiv.org/abs/2411.03042)