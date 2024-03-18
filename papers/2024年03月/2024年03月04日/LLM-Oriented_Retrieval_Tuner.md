# 针对 LLM 的检索优化器，旨在对大型语言模型进行精准高效的检索调优。

发布时间：2024年03月04日

`RAG`

> LLM-Oriented Retrieval Tuner

> 当前，DR技术被寄予厚望，通过融入外部记忆资源显著提升GPT-3、GPT-4等LLM的记忆力。然而，由于LLM文本生成机制与DR技术的本质差异，如何无缝结合LLM中的检索与生成任务仍是一个亟待解决的问题。为此，我们创新性地设计出一款面向LLM的高效检索优化器LMORT，它巧妙地将LLM的基础检索能力解耦出来，温和地引导LLM各层次结构最优适配并均匀映射至一个统一的DR空间，进而实现在不改变LLM自身参数的前提下，高效而精准地执行DR任务。大规模实验结果显示，在六个BEIR数据集上，我们的方法在保持LLM原有生成能力的同时，其零样本检索性能可媲美众多顶尖DR模型。

> Dense Retrieval (DR) is now considered as a promising tool to enhance the memorization capacity of Large Language Models (LLM) such as GPT3 and GPT-4 by incorporating external memories. However, due to the paradigm discrepancy between text generation of LLM and DR, it is still an open challenge to integrate the retrieval and generation tasks in a shared LLM. In this paper, we propose an efficient LLM-Oriented Retrieval Tuner, namely LMORT, which decouples DR capacity from base LLM and non-invasively coordinates the optimally aligned and uniform layers of the LLM towards a unified DR space, achieving an efficient and effective DR without tuning the LLM itself. The extensive experiments on six BEIR datasets show that our approach could achieve competitive zero-shot retrieval performance compared to a range of strong DR models while maintaining the generation ability of LLM.

[Arxiv](https://arxiv.org/abs/2403.01999)