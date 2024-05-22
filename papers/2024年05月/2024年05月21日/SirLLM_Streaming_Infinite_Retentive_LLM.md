# SirLLM：大型语言模型的流式无限记忆技术

发布时间：2024年05月21日

`LLM应用

这篇论文介绍了一种新型的LLM（大型语言模型）应用，即流式无限记忆LLM（SirLLM）。该模型通过特定的机制（令牌熵度量和记忆衰减机制）来处理和记忆任意长度的输入，特别适用于需要长时间记忆的对话场景。论文通过实验验证了SirLLM在多个任务上的有效性，并公开了相关代码。因此，这篇论文属于LLM应用类别。` `对话系统`

> SirLLM: Streaming Infinite Retentive LLM

# 摘要

> 随着大型语言模型（LLMs）在多领域的广泛应用，其处理任意长度输入并保持记忆的能力愈发关键。但一次性处理过长文本的能力受限，一旦超出预训练文本长度，文本生成能力便大幅下滑。延长预训练文本长度因数据获取难和内存成本高而不可行。为此，我们引入了流式无限记忆LLM（SirLLM），它无需微调即可在无限长对话中保持更长记忆。SirLLM通过令牌熵度量和记忆衰减机制筛选关键短语，赋予LLMs持久且灵活的记忆。我们设计了三个任务并构建了三个数据集，从多角度评估SirLLM的有效性：日常对话、杂货购物、石头剪刀布。实验结果有力证明，SirLLM在不同LLMs和任务上均能实现稳定且显著的改进，充分验证了其有效性。在对话中，“一位先生可能会忘记自己”，但SirLLM绝不会如此！我们的代码已公开在https://github.com/Zoeyyao27/SirLLM。

> As Large Language Models (LLMs) become increasingly prevalent in various domains, their ability to process inputs of any length and maintain a degree of memory becomes essential. However, the one-off input of overly long texts is limited, as studies have shown that when input lengths exceed the LLMs' pre-trained text length, there is a dramatic decline in text generation capabilities. Moreover, simply extending the length of pre-training texts is impractical due to the difficulty in obtaining long text data and the substantial memory consumption costs this would entail for LLMs. Recent efforts have employed streaming inputs to alleviate the pressure of excessively long text inputs, but this approach can significantly impair the model's long-term memory capabilities.
  Motivated by this challenge, we introduce Streaming Infinite Retentive LLM (SirLLM), which allows LLMs to maintain longer memory during infinite-length dialogues without the need for fine-tuning. SirLLM utilizes the Token Entropy metric and a memory decay mechanism to filter key phrases, endowing LLMs with both long-lasting and flexible memory. We designed three distinct tasks and constructed three datasets to measure the effectiveness of SirLLM from various angles: (1) DailyDialog; (2) Grocery Shopping; (3) Rock-Paper-Scissors. Our experimental results robustly demonstrate that SirLLM can achieve stable and significant improvements across different LLMs and tasks, compellingly proving its effectiveness. When having a coversation, "A sir could forget himself," but SirLLM never does! Our code is publicly available at https://github.com/Zoeyyao27/SirLLM

[Arxiv](https://arxiv.org/abs/2405.12528)