# [CFRet-DVQA 是一种创新的方法，应用于文档视觉问答任务中，通过粗到细的检索策略和高效的模型微调技术，旨在提升问题解答的准确性和效率。](https://arxiv.org/abs/2403.00816)

发布时间：2024年02月25日

`LLM应用`

> CFRet-DVQA: Coarse-to-Fine Retrieval and Efficient Tuning for Document Visual Question Answering

> DVQA任务要求根据图片内容解答问题，但现有技术仅能处理单页内的信息定位，无法实现跨页问答，并且模型对输入的字符长度限制可能造成与答案相关的关键信息缺失。本文提出了一项新颖而实用的方案——CFRet-DVQA，聚焦于信息检索及高效优化策略，针对性地解决了这一瓶颈问题。首先，我们从文档中智能检索与问题紧密关联的多个文本片段；随后，借助大型语言模型（LLM）强大的推理能力，并结合指令微调技术进一步提升模型表现力。这样，生成的答案就能贴合文档标签本身的表达风格。实验结果显示，在多种类型的单页文档和多页文档数据集上，我们的方法均达到了最新水平或与最优方法相媲美的效果。

> Document Visual Question Answering (DVQA) is a task that involves responding to queries based on the content of images. Existing work is limited to locating information within a single page and does not facilitate cross-page question-and-answer interaction. Furthermore, the token length limitation imposed on inputs to the model may lead to truncation of segments pertinent to the answer. In this study, we introduce a simple but effective methodology called CFRet-DVQA, which focuses on retrieval and efficient tuning to address this critical issue effectively. For that, we initially retrieve multiple segments from the document that correlate with the question at hand. Subsequently, we leverage the advanced reasoning abilities of the large language model (LLM), further augmenting its performance through instruction tuning. This approach enables the generation of answers that align with the style of the document labels. The experiments demonstrate that our methodology achieved state-of-the-art or competitive results with both single-page and multi-page documents in various fields.

[Arxiv](https://arxiv.org/abs/2403.00816)