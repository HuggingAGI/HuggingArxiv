# 结合语言模型与医学本体，实现西班牙语临床笔记中的病理自动检测

发布时间：2024年10月01日

`LLM应用` `皮肤病理`

> Detección Automática de Patologías en Notas Clínicas en Español Combinando Modelos de Lenguaje y Ontologías Médicos

# 摘要

> 本文介绍了一种结合大型语言模型和医学本体的混合方法，用于自动检测医疗报告中的皮肤病理。通过分析初次或后续报告，模型能预测患者可能的病理。研究显示，模型若能按序学习病理的类型、严重程度和身体部位，其准确性将大幅提升。我们实现了0.84的精确度，微观和宏观F1分数分别为0.82和0.75，并将此方法和数据集公开，供社区使用。

> In this paper we present a hybrid method for the automatic detection of dermatological pathologies in medical reports. We use a large language model combined with medical ontologies to predict, given a first appointment or follow-up medical report, the pathology a person may suffer from. The results show that teaching the model to learn the type, severity and location on the body of a dermatological pathology as well as in which order it has to learn these three features significantly increases its accuracy. The article presents the demonstration of state-of-the-art results for classification of medical texts with a precision of 0.84, micro and macro F1-score of 0.82 and 0.75, and makes both the method and the dataset used available to the community.
  --
  En este artículo presentamos un método híbrido para la detección automática de patologías dermatológicas en informes médicos. Usamos un modelo de lenguaje amplio en español combinado con ontologías médicas para predecir, dado un informe médico de primera cita o de seguimiento, la patología del paciente. Los resultados muestran que el tipo, la gravedad y el sitio en el cuerpo de una patología dermatológica, así como en qué orden tiene un modelo que aprender esas tres características, aumentan su precisión. El artículo presenta la demostración de resultados comparables al estado del arte de clasificación de textos médicos con una precisión de 0.84, micro y macro F1-score de 0.82 y 0.75, y deja a disposición de la comunidad tanto el método como el conjunto de datos utilizado.

[Arxiv](https://arxiv.org/abs/2410.00616)