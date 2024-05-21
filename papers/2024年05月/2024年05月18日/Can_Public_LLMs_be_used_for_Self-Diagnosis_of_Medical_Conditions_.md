# 公共LLMs是否能助力自我诊断医疗状况？

发布时间：2024年05月18日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在医疗保健领域，特别是在自我诊断医疗状况任务中的应用。论文通过构建一个包含10000样本的提示工程数据集，并测试了GPT-4.0与Gemini模型在自我诊断任务上的表现，对比了它们的性能，并探讨了这些模型在该任务上的挑战、局限与潜力。此外，论文还展示了通过检索增强生成（RAG）在自我诊断任务上的性能提升潜力。因此，这篇论文更符合LLM应用分类，因为它关注的是LLMs在特定应用场景（医疗自我诊断）中的实际应用和性能评估。` `医疗保健` `自我诊断`

> Can Public LLMs be used for Self-Diagnosis of Medical Conditions ?

# 摘要

> 大型语言模型（LLMs）的进步，已将对话任务推向一个新纪元，并逐渐融入医疗保健的核心领域。随着LLMs的普及和开源模型的公开访问，探究其潜能与局限变得尤为重要。其中，自我诊断医疗状况这一任务，虽已应用LLMs，但对其理解尚需深化，这对公共卫生意义重大。Gemini与Google搜索、GPT-4.0与Bing搜索的结合，改变了自我诊断的趋势。本文中，我们构建了一个包含10000样本的提示工程数据集，并测试了在自我诊断任务上的表现。我们对比了GPT-4.0与Gemini模型的性能，其准确率分别为63.07%和6.01%。同时，我们探讨了这两个模型在自我诊断任务上的挑战、局限与潜力，旨在推动未来研究并扩大其对公众知识的影响。此外，我们还展示了通过检索增强生成在自我诊断任务上的性能提升潜力。

> The advancements in the development of Large Language Models have evolved as a transformative paradigm in conversational tasks which has led to its integration in the critical domain of healthcare. With LLMs becoming widely popular and their public access through open-source models, there is a need to investigate their potential and limitations. One such critical task where LLMs are applied but require a deeper understanding is that of self-diagnosis of medical conditions in the interest of public health. The widespread integration of Gemini with Google search, GPT-4.0 with Bing search, has led to shift in trend of self-diagnosis from search engine LLMs. In this paper, we prepare a prompt engineered dataset of 10000 samples and test the performance on the general task of self-diagnosis. We compare the performance of GPT-4.0 and Gemini model on the task of self-diagnosis and record accuracies of 63.07% and 6.01% respectively. We also discuss the challenges, limitations, and potential of both Gemini and GPT-4.0 for the task of self-diagnosis to facilitate future research and towards the broader impact of general public knowledge. Furthermore, we demonstrate the potential and improvement in performance for the task of self-diagnosis using Retrieval Augmented Generation.

[Arxiv](https://arxiv.org/abs/2405.11407)