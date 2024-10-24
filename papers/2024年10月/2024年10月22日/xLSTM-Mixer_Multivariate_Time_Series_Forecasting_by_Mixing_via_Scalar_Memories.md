# xLSTM-Mixer：通过标量记忆混合进行多元时间序列预测

发布时间：2024年10月22日

`其他` `时间序列` `预测模型`

> xLSTM-Mixer: Multivariate Time Series Forecasting by Mixing via Scalar Memories

# 摘要

> 摘要：时间序列数据在众多领域中普遍存在，这就需要开发强大且准确的预测模型。捕捉时间和多元组件内部及之间的模式对于可靠的预测至关重要。我们引入 xLSTM-Mixer，这是一个旨在有效整合时间序列、联合时变信息和多个视角以进行稳健预测的模型。我们的方法从跨变量共享的线性预测开始，然后由 xLSTM 块进行细化。这些块是对具有挑战性的时间序列数据的复杂动态进行建模的关键元素。xLSTM-Mixer 最终协调了两种不同的观点以产生最终预测。我们广泛的评估表明，与最近的最先进方法相比，xLSTM-Mixer 具有优越的长期预测性能。彻底的模型分析进一步深入了解其关键组件，并确认其稳健性和有效性。这项工作有助于循环模型在时间序列预测中的复兴。

> 
Abstract:Time series data is prevalent across numerous fields, necessitating the development of robust and accurate forecasting models. Capturing patterns both within and between temporal and multivariate components is crucial for reliable predictions. We introduce xLSTM-Mixer, a model designed to effectively integrate temporal sequences, joint time-variate information, and multiple perspectives for robust forecasting. Our approach begins with a linear forecast shared across variates, which is then refined by xLSTM blocks. These blocks serve as key elements for modeling the complex dynamics of challenging time series data. xLSTM-Mixer ultimately reconciles two distinct views to produce the final forecast. Our extensive evaluations demonstrate xLSTM-Mixer's superior long-term forecasting performance compared to recent state-of-the-art methods. A thorough model analysis provides further insights into its key components and confirms its robustness and effectiveness. This work contributes to the resurgence of recurrent models in time series forecasting.
    

[Arxiv](https://arxiv.org/pdf/2410.16928)