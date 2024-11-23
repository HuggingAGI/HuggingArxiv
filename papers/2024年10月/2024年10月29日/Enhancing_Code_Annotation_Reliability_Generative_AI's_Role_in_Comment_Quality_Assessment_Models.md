# 提升代码注释的可靠性：生成式 AI 在注释质量评估模型里的角色

发布时间：2024年10月29日

`LLM应用` `软件工程` `软件开发`

> Enhancing Code Annotation Reliability: Generative AI's Role in Comment Quality Assessment Models

# 摘要

> 这篇论文探索了一种增强评估代码注释质量的二分类模型的新办法，借助生成式人工智能来提高模型性能。将 1437 个新生成的代码 - 注释对（标记为“有用”或“无用”，源自各类 GitHub 库）融入现有的 9048 对的 C 语言数据集中，我们展现出了显著的模型改进效果。运用先进的大型语言模型，我们的方法让支持向量机（SVM）模型的精度提升了 5.78%，从 0.79 升至 0.8478，还使人工神经网络（ANN）模型的召回率提高了 2.17%，从 0.731 涨至 0.7527。这些成果凸显了生成式人工智能在推进代码注释分类模型上的价值，为提升软件开发和质量控制的准确性带来巨大潜力。此项研究为在实际软件工程场景中融合生成技术来优化机器学习模型提供了光明前景。

> This paper explores a novel method for enhancing binary classification models that assess code comment quality, leveraging Generative Artificial Intelligence to elevate model performance. By integrating 1,437 newly generated code-comment pairs, labeled as "Useful" or "Not Useful" and sourced from various GitHub repositories, into an existing C-language dataset of 9,048 pairs, we demonstrate substantial model improvements. Using an advanced Large Language Model, our approach yields a 5.78% precision increase in the Support Vector Machine (SVM) model, improving from 0.79 to 0.8478, and a 2.17% recall boost in the Artificial Neural Network (ANN) model, rising from 0.731 to 0.7527. These results underscore Generative AI's value in advancing code comment classification models, offering significant potential for enhanced accuracy in software development and quality control. This study provides a promising outlook on the integration of generative techniques for refining machine learning models in practical software engineering settings.

[Arxiv](https://arxiv.org/abs/2410.22323)