# ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。

发布时间：2024年03月11日

`LLM应用`

> ConspEmoLLM: Conspiracy Theory Detection Using an Emotion-Based Large Language Model

# 摘要

> 互联网犹如一把双刃剑，既带来便利也滋生了诸如阴谋论等误导性信息在网络上的泛滥。随着自然语言处理技术的突破，尤其是大型语言模型（LLMs）的兴起，精准检测错误信息变得更为可行。不过，现有基于LLM的阴谋论识别大多局限于简单的二元分类，忽视了错误信息与情感特征间的紧密联系。鉴于此，通过对阴谋论文本深入剖析，并捕捉其独特的情感特质，我们创新提出ConspEmoLLM——首个整合情感信息且开源的多功能LLM，不仅能高效甄别阴谋论，还能进一步细分理论类别，追踪相关讨论（如针对理论的意见）。ConspEmoLLM是在一个注重情感维度的LLM基础上，采用我们独家构建的ConDID数据集进行精细化调整，该数据集包含了五个任务用以指导LLM的优化训练与效果评测。实验表明，在应对上述任务时，ConspEmoLLM展现出显著优势，超越了几款主流开源LLMs及ChatGPT，甚至比经过ConDID微调但未融入情感特征的LLM表现更优。这款项目即将在https://github.com/lzw108/ConspEmoLLM/上线发布。

> The internet has brought both benefits and harms to society. A prime example of the latter is misinformation, including conspiracy theories, which flood the web. Recent advances in natural language processing, particularly the emergence of large language models (LLMs), have improved the prospects of accurate misinformation detection. However, most LLM-based approaches to conspiracy theory detection focus only on binary classification and fail to account for the important relationship between misinformation and affective features (i.e., sentiment and emotions). Driven by a comprehensive analysis of conspiracy text that reveals its distinctive affective features, we propose ConspEmoLLM, the first open-source LLM that integrates affective information and is able to perform diverse tasks relating to conspiracy theories. These tasks include not only conspiracy theory detection, but also classification of theory type and detection of related discussion (e.g., opinions towards theories). ConspEmoLLM is fine-tuned based on an emotion-oriented LLM using our novel ConDID dataset, which includes five tasks to support LLM instruction tuning and evaluation. We demonstrate that when applied to these tasks, ConspEmoLLM largely outperforms several open-source general domain LLMs and ChatGPT, as well as an LLM that has been fine-tuned using ConDID, but which does not use affective features. This project will be released on https://github.com/lzw108/ConspEmoLLM/.

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x1.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x2.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x3.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x4.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x5.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x6.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x7.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x8.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x9.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x10.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x11.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x12.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x13.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x14.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x15.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x16.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x17.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x18.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x19.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x20.png)

![ConspEmoLLM是一种运用情感导向的大规模语言模型进行阴谋论检测的技术，它利用深度学习和自然语言处理技术来识别文本中的潜在阴谋论信息。](../../../paper_images/2403.06765/x21.png)

[Arxiv](https://arxiv.org/abs/2403.06765)