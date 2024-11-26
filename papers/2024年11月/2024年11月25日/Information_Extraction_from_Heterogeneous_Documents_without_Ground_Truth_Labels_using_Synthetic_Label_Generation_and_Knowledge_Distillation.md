# 利用合成标签生成与知识蒸馏，从无真实标签的异构文档中提取信息

发布时间：2024年11月25日

`LLM应用` `文档处理`

> Information Extraction from Heterogeneous Documents without Ground Truth Labels using Synthetic Label Generation and Knowledge Distillation

# 摘要

> 员工提交的发票和收据属于视觉丰富文档（VRDs），涵盖文本、视觉和布局等信息。为防范欺诈与滥用风险，组织能高效地从提交的收据中提取所需信息极为关键。这有助于评估诸如费用报销是否恰当、是否遵循支出和交易政策、收据是否有效，以及各层面的下游异常检测等关键要素。这些文档具有异构性，格式和语言多样，上传的图像质量各异，且通常缺少用于有效训练模型的真实标签。本文提出了任务感知指令标注（TAIL）法，用于在无标签的 VRD 语料库中生成合成标签，并运用基于响应的知识蒸馏，在 TAIL 标签上对多模态视觉丰富文档理解模型（VRDU）进行微调，无需使用教师模型的权重或训练数据集，就能有条件地生成合适格式的注释。通过使用具备真实标签的基准外部数据集，我们经实证研究证明了本方法与 Claude 3 Sonnet 表现相当的条件。接着，我们展示所得模型在一家大型跨国组织的内部费用文档上的表现不逊于甚至优于最先进的大型多模态模型 Claude 3 Sonnet，成本降低 85%，速度快约 5 倍，而且因其能从罕见格式中推理和提取信息，在平均归一化莱文斯坦相似度（ANLS）得分上比布局感知基线高出 10%以上。最后，我们阐述了本方法在防止超额支付方面的应用。

> Invoices and receipts submitted by employees are visually rich documents (VRDs) with textual, visual and layout information. To protect against the risk of fraud and abuse, it is crucial for organizations to efficiently extract desired information from submitted receipts. This helps in the assessment of key factors such as appropriateness of the expense claim, adherence to spending and transaction policies, the validity of the receipt, as well as downstream anomaly detection at various levels. These documents are heterogeneous, with multiple formats and languages, uploaded with different image qualities, and often do not contain ground truth labels for the efficient training of models. In this paper we propose Task Aware Instruction-based Labelling (TAIL), a method for synthetic label generation in VRD corpuses without labels, and fine-tune a multimodal Visually Rich Document Understanding Model (VRDU) on TAIL labels using response-based knowledge distillation without using the teacher model's weights or training dataset to conditionally generate annotations in the appropriate format. Using a benchmark external dataset where ground truth labels are available, we demonstrate conditions under which our approach performs at par with Claude 3 Sonnet through empirical studies. We then show that the resulting model performs at par or better on the internal expense documents of a large multinational organization than state-of-the-art LMM (large multimodal model) Claude 3 Sonnet while being 85% less costly and ~5X faster, and outperforms layout-aware baselines by more than 10% in Average Normalized Levenshtein Similarity (ANLS) scores due to its ability to reason and extract information from rare formats. Finally, we illustrate the usage of our approach in overpayment prevention.

[Arxiv](https://arxiv.org/abs/2411.14957)