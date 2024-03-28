# 致力于构建一款既可靠又便于使用的照护语言模型（CaLM），旨在提升照护服务领域的沟通与智能化水平。

发布时间：2024年03月11日

`Agent`

> Development of a Reliable and Accessible Caregiving Language Model (CaLM)

# 摘要

> 不同于有专业训练背景的护工，家庭护理员往往临危受命，缺乏充分的准备和培训。因此，提升家庭护理员提供优质照护能力的需求日益迫切。大型语言模型有望作为技术支持，服务于护理员教育或辅助照护工作。本研究致力于研发一款基于预训练模型（简称FM）和护理专业知识库的可靠“护理语言模型”（CaLM），并通过运用小型FM降低对计算资源的需求，使之更加便捷实用，同时对比其与大型FM的性能差异。我们采用了“检索增强生成”（RAG）框架，并结合FM的精细调整，让CaLM扎根于护理知识库，从而提升模型输出答案的准确性。实验选用两个小型FM（包括LLaMA-2和拥有70亿参数的Falcon）作为CaLM的FM备选方案，并以大型FM GPT-3.5作为参照基准。我们从互联网上搜集各类资料，创建了一个专门针对阿尔茨海默病相关痴呆症患者照护的护理知识库。研究过程中，我们借助通用的语言模型评测指标以及模型能否提供精确参考答案的能力进行了详尽的性能评估。结果显示，RAG框架有效地提升了本研究中所有FM的各项性能指标。意料之中的是，大型FM在所有指标上均优于小型FM。然而，令人惊喜的是，经微调后的小型FM在融合了RAG技术后，在所有评测指标上均大幅超越了GPT 3.5。特别是在返回包含答案的参考资料方面，经过微调的LLaMA-2小型FM即使面对配备了RAG的GPT 3.5也表现出色。此项研究揭示，通过巧妙利用针对护理领域的特定知识库和小型FM，完全可以打造出既可靠又亲民的CaLM。

> Unlike professional caregivers, family caregivers often assume this role without formal preparation or training. Because of this, there is an urgent need to enhance the capacity of family caregivers to provide quality care. Large language models can potentially be used as a foundation technology for supporting caregivers as educational tools or as adjunct to care. This study aimed to develop a reliable Caregiving Language Model (CaLM) by using FMs and a caregiving knowledge base, develop an accessible CaLM using a small FM that requires fewer computing resources, and evaluate the performance of the model compared to a large FM. We developed CaLM using the Retrieval Augmented Generation (RAG) framework combined with FM fine-tuning for improving the quality of FM answers by grounding the model on a caregiving knowledge base. We used two small FMs as candidates for the FM of CaLM (LLaMA-2 and Falcon with 7B parameters) and larger FM GPT-3.5 as a benchmark. We developed the caregiving knowledge base by gathering various types of documents from the Internet. In this study, we focused on caregivers of individuals with Alzheimer's Disease Related Dementias. We evaluated the models' performance using the benchmark metrics commonly used in evaluating language models and their reliability to provide accurate references with the answers. The RAG framework improved the performance of all FMs used in this study across all measures. As expected, the large FM performed better than small FMs across all metrics. The most interesting result is that small fine-tuned FMs with RAG performed significantly better than GPT 3.5 across all metrics. The fine-tuned LLaMA-2 small FM performed better than GPT 3.5 (even with RAG) in returning references with the answers. The study shows that reliable and accessible CaLM can be developed by using small FMs with a knowledge base specific to the caregiving domain.

[Arxiv](https://arxiv.org/abs/2403.06857)