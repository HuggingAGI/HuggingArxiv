# LLM-DetectAIve：一款精密的机器生成文本检测工具

发布时间：2024年08月08日

`LLM应用`

> LLM-DetectAIve: a Tool for Fine-Grained Machine-Generated Text Detection

# 摘要

> 随着大型语言模型 (LLM) 对公众的广泛开放，机器生成文本 (MGT) 的传播大幅增加。提示技术的进步使得区分文本是由人类还是机器生成变得更加困难，这引发了关于 MGT 在教育和学术领域滥用的担忧。为此，我们推出了 $\textbf{LLM-DetectAIve}$ 系统，专门用于精细区分 MGT。该系统能将文本细分为四类：纯人类撰写、纯机器生成、机器撰写但经人性化处理，以及人类撰写但经机器润色。与传统的二元分类检测器不同，LLM-DetectAIve 的额外分类有助于揭示 LLM 在文本创作中的不同介入程度，这在教育等禁止 LLM 介入的领域尤为重要。实验证明，LLM-DetectAIve 能有效识别文本作者，增强教育、学术等领域的诚信。该系统已公开，可访问 https://huggingface.co/spaces/raj-tomar001/MGT-New，相关介绍视频见 https://youtu.be/E8eT_bE7k8c。

> The widespread accessibility of large language models (LLMs) to the general public has significantly amplified the dissemination of machine-generated texts (MGTs). Advancements in prompt manipulation have exacerbated the difficulty in discerning the origin of a text (human-authored vs machinegenerated). This raises concerns regarding the potential misuse of MGTs, particularly within educational and academic domains. In this paper, we present $\textbf{LLM-DetectAIve}$ -- a system designed for fine-grained MGT detection. It is able to classify texts into four categories: human-written, machine-generated, machine-written machine-humanized, and human-written machine-polished. Contrary to previous MGT detectors that perform binary classification, introducing two additional categories in LLM-DetectiAIve offers insights into the varying degrees of LLM intervention during the text creation. This might be useful in some domains like education, where any LLM intervention is usually prohibited. Experiments show that LLM-DetectAIve can effectively identify the authorship of textual content, proving its usefulness in enhancing integrity in education, academia, and other domains. LLM-DetectAIve is publicly accessible at https://huggingface.co/spaces/raj-tomar001/MGT-New. The video describing our system is available at https://youtu.be/E8eT_bE7k8c.

[Arxiv](https://arxiv.org/abs/2408.04284)