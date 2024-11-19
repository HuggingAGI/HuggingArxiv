# 大型语言模型能否预测员工的流失情况？

发布时间：2024年11月02日

`LLM应用` `人力资源` `机器学习`

> Can Large Language Model Predict Employee Attrition?

# 摘要

> 员工流失给组织造成了重大成本，传统的统计预测手段常常难以把控现代劳动力的复杂性。机器学习（ML）的发展带来了更具扩展性和精确性的解决办法，而大型语言模型（LLMs）通过解读员工细微的交流和察觉微妙的离职迹象，为人力资源管理带来了新的可能。本研究借助 IBM HR 分析员工流失数据集，对微调后的 GPT-3.5 模型和传统的 ML 分类器（包含逻辑回归、k 近邻（KNN）、支持向量机（SVM）、决策树、随机森林、AdaBoost 以及 XGBoost）的预测准确性和可解释性进行了比较。尽管传统模型更便于使用和解释，LLMs 却能够揭示员工行为中的深层模式。我们的发现显示，微调后的 GPT-3.5 模型优于传统方法，其精度为 0.91，召回率为 0.94，F1 分数为 0.92，而传统模型中表现最佳的 SVM 的 F1 分数为 0.82，随机森林和 XGBoost 则达到 0.80。这些结果凸显了 GPT-3.5 捕捉员工流失风险复杂模式的能力，为组织的留存策略提供了更好的见解，也突显了 LLMs 在人力资源应用中的价值。

> Employee attrition poses significant costs for organizations, with traditional statistical prediction methods often struggling to capture modern workforce complexities. Machine learning (ML) advancements offer more scalable and accurate solutions, but large language models (LLMs) introduce new potential in human resource management by interpreting nuanced employee communication and detecting subtle turnover cues. This study leverages the IBM HR Analytics Attrition dataset to compare the predictive accuracy and interpretability of a fine-tuned GPT-3.5 model against traditional ML classifiers, including Logistic Regression, k-Nearest Neighbors (KNN), Support Vector Machine (SVM), Decision Tree, Random Forest, AdaBoost, and XGBoost. While traditional models are easier to use and interpret, LLMs can reveal deeper patterns in employee behavior. Our findings show that the fine-tuned GPT-3.5 model outperforms traditional methods with a precision of 0.91, recall of 0.94, and an F1-score of 0.92, while the best traditional model, SVM, achieved an F1-score of 0.82, with Random Forest and XGBoost reaching 0.80. These results highlight GPT-3.5's ability to capture complex patterns in attrition risk, offering organizations improved insights for retention strategies and underscoring the value of LLMs in HR applications.

[Arxiv](https://arxiv.org/abs/2411.01353)