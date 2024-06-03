# 视觉角色扮演：利用角色扮演图像角色对多模态大型语言模型实施通用越狱攻击

发布时间：2024年05月25日

`Agent

这篇论文主要探讨了多模态大型语言模型（MLLMs）的安全性问题，并提出了一种新的攻击方法——视觉角色扮演（VRP）。这种方法通过利用大型语言模型生成高风险角色的详细描述，并据此创建图像，以误导MLLMs生成恶意响应。这种研究更偏向于Agent的范畴，因为它涉及创建和利用特定的攻击策略来影响模型的行为，类似于一个智能Agent的行为。此外，这种方法的提出和实验验证也展示了其在实际应用中的潜在影响，进一步强化了其作为Agent类研究的定位。` `网络安全` `人工智能安全`

> Visual-RolePlay: Universal Jailbreak Attack on MultiModal Large Language Models via Role-playing Image Characte

# 摘要

> 随着多模态大型语言模型（MLLMs）的普及，其安全性问题日益凸显。为了确保安全，我们需要主动识别MLLMs的弱点，探索各种攻击手段。其中，基于结构的越狱攻击通过在图像中嵌入有害内容来误导模型。然而，以往的方法多集中在恶意查询格式的转换，如通过排版将有害内容图像化，这种方法的越狱效果和通用性不足。为此，我们引入了“角色扮演”概念，并提出了一种名为视觉角色扮演（VRP）的新方法。VRP利用大型语言模型生成高风险角色的详细描述，并据此创建图像。结合良性的角色扮演指令，这些图像能有效误导MLLMs生成恶意响应。我们还扩展了VRP方法，证明了其通用性。实验结果显示，VRP在所有模型上的平均攻击成功率比最强基线高出14.3%。

> With the advent and widespread deployment of Multimodal Large Language Models (MLLMs), ensuring their safety has become increasingly critical. To achieve this objective, it requires us to proactively discover the vulnerability of MLLMs by exploring the attack methods. Thus, structure-based jailbreak attacks, where harmful semantic content is embedded within images, have been proposed to mislead the models. However, previous structure-based jailbreak methods mainly focus on transforming the format of malicious queries, such as converting harmful content into images through typography, which lacks sufficient jailbreak effectiveness and generalizability. To address these limitations, we first introduce the concept of "Role-play" into MLLM jailbreak attacks and propose a novel and effective method called Visual Role-play (VRP). Specifically, VRP leverages Large Language Models to generate detailed descriptions of high-risk characters and create corresponding images based on the descriptions. When paired with benign role-play instruction texts, these high-risk character images effectively mislead MLLMs into generating malicious responses by enacting characters with negative attributes. We further extend our VRP method into a universal setup to demonstrate its generalizability. Extensive experiments on popular benchmarks show that VRP outperforms the strongest baseline, Query relevant and FigStep, by an average Attack Success Rate (ASR) margin of 14.3% across all models.

![视觉角色扮演：利用角色扮演图像角色对多模态大型语言模型实施通用越狱攻击](../../../paper_images/2405.20773/x1.png)

[Arxiv](https://arxiv.org/abs/2405.20773)