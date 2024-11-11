# 控制未观察到的混杂因素与大型语言模型对患者吸烟状况的分类

发布时间：2024年11月05日

`LLM应用` `因果推断`

> Controlling for Unobserved Confounding with Large Language Model Classification of Patient Smoking Status

# 摘要

> 因果理解是循证医学的一个基本目标。当随机化不可能时，因果推断方法允许从观察数据的回顾性分析中估计治疗效果。然而，这种分析依赖于许多假设，通常包括不存在未观察到的混杂因素。在许多实际情况下，当重要变量在临床记录中未明确测量时，这个假设就会被违反。先前的工作提出通过机器学习来解决未观察到的混杂因素，方法是估算未观察到的变量，然后校正分类器的测量误差。当这样的分类器可以训练并且必要的假设得到满足时，这种方法可以恢复因果效应的无偏估计。然而，这样的工作仅限于合成数据、简单的分类器和二元变量。本文通过使用在临床笔记上训练的大型语言模型来预测患者的吸烟状况（否则这将是一个未观察到的混杂因素）扩展了这种方法。然后，我们对分类预测的吸烟状况应用测量误差校正，以估计经胸超声心动图对 MIMIC 数据集中死亡率的因果效应。

> Causal understanding is a fundamental goal of evidence-based medicine. When randomization is impossible, causal inference methods allow the estimation of treatment effects from retrospective analysis of observational data. However, such analyses rely on a number of assumptions, often including that of no unobserved confounding. In many practical settings, this assumption is violated when important variables are not explicitly measured in the clinical record. Prior work has proposed to address unobserved confounding with machine learning by imputing unobserved variables and then correcting for the classifier's mismeasurement. When such a classifier can be trained and the necessary assumptions are met, this method can recover an unbiased estimate of a causal effect. However, such work has been limited to synthetic data, simple classifiers, and binary variables. This paper extends this methodology by using a large language model trained on clinical notes to predict patients' smoking status, which would otherwise be an unobserved confounder. We then apply a measurement error correction on the categorical predicted smoking status to estimate the causal effect of transthoracic echocardiography on mortality in the MIMIC dataset.

[Arxiv](https://arxiv.org/abs/2411.03004)