# 借助摘要引导解码技术，有效缓解大型视觉语言模型中的幻觉问题。

发布时间：2024年10月17日

`LLM应用` `计算机视觉`

> Mitigating Hallucinations in Large Vision-Language Models via Summary-Guided Decoding

# 摘要

> 大型视觉-语言模型 (LVLMs) 在生成视觉输入的详细且连贯的响应方面表现出色，但过度依赖语言先验导致幻觉问题。我们研究发现：(1) 随着标记序列增长，模型在预测图像相关词性时越来越依赖语言先验，加剧幻觉。(2) 直接校准输出分布的方法可能降低文本质量，甚至加剧幻觉。为此，我们提出摘要引导解码 (SGD)，通过减少文本上下文并控制图像相关词性标记，自然地引导模型关注图像信息，同时保持文本质量。实验表明，SGD 在对象幻觉基准测试中表现卓越，并在精确率和召回率权衡上达到帕累托最优。此外，SGD 在平衡幻觉减少与文本质量保持方面表现稳健。

> Large Vision-Language Models (LVLMs) demonstrate impressive capabilities in generating detailed and coherent responses from visual inputs. However, they are prone to generate hallucinations due to an over-reliance on language priors. To address this issue, we investigate the language priors in LVLMs and make two key observations: (1) Even when predicting the tokens associated with image-related part-of-speech (POS), models increasingly rely on linguistic priors as the token sequences grow, thereby amplifying hallucinations. (2) Methods that directly calibrate LVLM's output distribution to mitigate language priors can lead to a degradation in text quality or even exacerbate hallucinations. Based on these findings, we propose a novel method, Summary-Guided Decoding (SGD). This method naturally encourages the model to focus more on image information by reducing the text context through summaries, while controlling only the image-related POS tokens to maintain text quality. Through experiments, we demonstrate that SGD achieves state-of-the-art performance on object hallucination benchmarks. Furthermore, in terms of the trade-off between precision and recall, SGD achieves Pareto optimality among the existing methods. Lastly, we observe that although existing methods struggle to balance the reduction of object hallucinations with maintaining text quality, SGD demonstrates robustness in handling this challenge.

[Arxiv](https://arxiv.org/abs/2410.13321)