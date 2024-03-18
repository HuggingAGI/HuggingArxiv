# [ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性]

发布时间：2024年03月11日

`LLM应用`

> ContextGPT: Infusing LLMs Knowledge into Neuro-Symbolic Activity Recognition Models

> 上下文感知人体活动识别（HAR）作为移动计算领域的热点，其最高效的解决方案主要依托于有监督的深度学习模型，但受限于训练所需标注数据的稀少，实际应用面临瓶颈。为解决这一问题，神经符号AI（NeSy）通过向HAR深度学习模型灌输关于人类活动及其执行环境的常识知识，开辟了一条引人关注的研究道路。不过，当前基于NeSy的上下文感知HAR方法大多依赖于逻辑模型（如本体论），其构建、实施及更新以捕获新活动和新上下文时，需要投入大量人工、技术和专业领域知识。最新研究表明，预训练的大型语言模型（LLMs）能有效蕴含关于人类活动的常识信息。为此，我们创新提出了ContextGPT，一种基于提示工程的新方法，旨在从LLMs中抽取出关于人类活动与其所处上下文间关系的常识知识。相较于本体论，ContextGPT所需的人力投入和专业知识更为有限。经过在两个公开数据集上的深入评估，我们发现融入来自ContextGPT常识知识的NeSy模型在数据匮乏情况下依然表现出色，往往只需要较少的努力就能达到甚至超越基于逻辑方法的识别准确率。

> Context-aware Human Activity Recognition (HAR) is a hot research area in mobile computing, and the most effective solutions in the literature are based on supervised deep learning models. However, the actual deployment of these systems is limited by the scarcity of labeled data that is required for training. Neuro-Symbolic AI (NeSy) provides an interesting research direction to mitigate this issue, by infusing common-sense knowledge about human activities and the contexts in which they can be performed into HAR deep learning classifiers. Existing NeSy methods for context-aware HAR rely on knowledge encoded in logic-based models (e.g., ontologies) whose design, implementation, and maintenance to capture new activities and contexts require significant human engineering efforts, technical knowledge, and domain expertise. Recent works show that pre-trained Large Language Models (LLMs) effectively encode common-sense knowledge about human activities. In this work, we propose ContextGPT: a novel prompt engineering approach to retrieve from LLMs common-sense knowledge about the relationship between human activities and the context in which they are performed. Unlike ontologies, ContextGPT requires limited human effort and expertise. An extensive evaluation carried out on two public datasets shows how a NeSy model obtained by infusing common-sense knowledge from ContextGPT is effective in data scarcity scenarios, leading to similar (and sometimes better) recognition rates than logic-based approaches with a fraction of the effort.

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/arch2.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/x1.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/x2.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/x3.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/x4.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/x5.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/symbolicfeatures.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/tool.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/plot_domino.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/plot_extrasensory.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/domino_boxplot.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/extrasensory_boxplot.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/domino_10.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/extrasensory_10.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/domino_50.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/extrasensory_50.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/domino_inclusion.png)

![ContextGPT：巧妙融合LLMs知识至神经符号活动识别模型中，提升模型性能与智能性](../../../paper_images/2403.06586/extrasensory_inclusion.png)

[Arxiv](https://arxiv.org/abs/2403.06586)