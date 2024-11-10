# 《语义中心假说：语言模型在不同语言和模态之间共享语义表示》

发布时间：2024年11月07日

`LLM理论` `语言模型` `神经科学`

> The Semantic Hub Hypothesis: Language Models Share Semantic Representations Across Languages and Modalities

# 摘要

> 现代语言模型可以处理多种语言和模态的输入。我们假设模型通过在不同数据类型（例如不同的语言和模态）之间学习共享表示空间来获得这种能力，该空间将语义相似的输入彼此靠近放置，即使它们来自不同的模态/语言。我们将此称为语义中心假设，遵循神经科学中的轮辐模型（Patterson 等人，2007 年），该模型假定人脑中的语义知识是通过跨模态语义“中心”组织的，该“中心”整合了来自各种特定模态“辐条”区域的信息。我们首先表明，不同语言中语义等效输入的模型表示在中间层是相似的，并且可以通过对数镜头使用模型的主要预训练语言来解释这个空间。这种趋势延伸到其他数据类型，包括算术表达式、代码以及视觉/音频输入。对一种数据类型的共享表示空间的干预也可预测地影响其他数据类型的模型输出，这表明这个共享表示空间不仅仅是在广泛数据上进行大规模训练的残余副产品，而是模型在输入处理过程中积极利用的东西。

> Modern language models can process inputs across diverse languages and modalities. We hypothesize that models acquire this capability through learning a shared representation space across heterogeneous data types (e.g., different languages and modalities), which places semantically similar inputs near one another, even if they are from different modalities/languages. We term this the semantic hub hypothesis, following the hub-and-spoke model from neuroscience (Patterson et al., 2007) which posits that semantic knowledge in the human brain is organized through a transmodal semantic "hub" which integrates information from various modality-specific "spokes" regions. We first show that model representations for semantically equivalent inputs in different languages are similar in the intermediate layers, and that this space can be interpreted using the model's dominant pretraining language via the logit lens. This tendency extends to other data types, including arithmetic expressions, code, and visual/audio inputs. Interventions in the shared representation space in one data type also predictably affect model outputs in other data types, suggesting that this shared representations space is not simply a vestigial byproduct of large-scale training on broad data, but something that is actively utilized by the model during input processing.

[Arxiv](https://arxiv.org/abs/2411.04986)