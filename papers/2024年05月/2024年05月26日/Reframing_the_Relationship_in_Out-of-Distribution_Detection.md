# 重塑分布外检测中的关系纽带

发布时间：2024年05月26日

`Agent

这篇论文探讨了将代理范式应用于分布外（OOD）检测任务，通过引入概念匹配代理（CMA）来提升检测的鲁棒性和适应性。这种方法利用中性提示作为代理，与分布内（ID）标签及数据输入互动，构建了一个向量三角关系，以更精细的策略区分和识别ID与OOD输入。因此，这篇论文属于Agent分类，因为它涉及使用代理来改进特定任务的性能。` `人工智能` `分布外检测`

> Reframing the Relationship in Out-of-Distribution Detection

# 摘要

> 大型语言模型（LLMs）的卓越成就不仅在对话生成领域引起了轰动，更在学术界和工业界掀起了一股热潮。作为多种任务的中介代理，LLMs展现出了巨大的潜力，推动了人工智能的创新浪潮。在此基础上，我们创新性地将代理范式融入分布外（OOD）检测任务，旨在提升其鲁棒性与适应性。我们的方法——概念匹配代理（CMA），巧妙地利用中性提示作为代理，强化了基于CLIP的OOD检测流程。这些代理如同动态的观察者和沟通枢纽，与分布内（ID）标签及数据输入互动，构建起向量三角关系。这一三角框架相较于传统的二元关系，提供了更为精细的策略，有效区分和识别ID与OOD输入。通过广泛的实验，我们证明了CMA在多样化的现实场景中，无论是零-shot还是需要训练的方法，均展现出卓越的性能。

> The remarkable achievements of Large Language Models (LLMs) have captivated the attention of both academia and industry, transcending their initial role in dialogue generation. The utilization of LLMs as intermediary agents in various tasks has yielded promising results, sparking a wave of innovation in artificial intelligence. Building on these breakthroughs, we introduce a novel approach that integrates the agent paradigm into the Out-of-distribution (OOD) detection task, aiming to enhance its robustness and adaptability. Our proposed method, Concept Matching with Agent (CMA), employs neutral prompts as agents to augment the CLIP-based OOD detection process. These agents function as dynamic observers and communication hubs, interacting with both In-distribution (ID) labels and data inputs to form vector triangle relationships. This triangular framework offers a more nuanced approach than the traditional binary relationship, allowing for better separation and identification of ID and OOD inputs. Our extensive experimental results showcase the superior performance of CMA over both zero-shot and training-required methods in a diverse array of real-world scenarios.

![重塑分布外检测中的关系纽带](../../../paper_images/2405.16766/x1.png)

![重塑分布外检测中的关系纽带](../../../paper_images/2405.16766/x2.png)

![重塑分布外检测中的关系纽带](../../../paper_images/2405.16766/x3.png)

![重塑分布外检测中的关系纽带](../../../paper_images/2405.16766/x4.png)

![重塑分布外检测中的关系纽带](../../../paper_images/2405.16766/x5.png)

[Arxiv](https://arxiv.org/abs/2405.16766)